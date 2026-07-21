# Compendium

Structured knowledge documents in LaTeX.

---

## Education Systems: USA & Europe

Comprehensive breakdown of K–12 and higher education systems across the United States and Europe.

**[View folder](ed-sys)** 

| | | | |
|---|---|---|---|
| [![](assets/ed-sys-01.png)](assets/ed-sys-01.png) | [![](assets/ed-sys-02.png)](assets/ed-sys-02.png) | [![](assets/ed-sys-03.png)](assets/ed-sys-03.png) | [![](assets/ed-sys-04.png)](assets/ed-sys-04.png) |
| [![](assets/ed-sys-05.png)](assets/ed-sys-05.png) | [![](assets/ed-sys-06.png)](assets/ed-sys-06.png) | [![](assets/ed-sys-07.png)](assets/ed-sys-07.png) | [![](assets/ed-sys-08.png)](assets/ed-sys-08.png) |

---

## Next Project Title Here

Description of next project.

**[View folder](next-project-folder)** 

| | | | |
|---|---|---|---|
| [![](assets/next-01.png)](assets/next-01.png) | [![](assets/next-02.png)](assets/next-02.png) | [![](assets/next-03.png)](assets/next-03.png) | [![](assets/next-04.png)](assets/next-04.png) |

---

## Build Requirements

- LaTeX distribution with `latexmk` and `lualatex`
- TeX Gyre fonts (Pagella, Heros Condensed)

## Workflow

Before building, clean output artifacts:

```bash
rm -rf output/
```

Then build once for a clean PDF:

```bash
latexmk -r latexmkrc main.tex
```

For live editing with auto-recompile, open three terminal panes:

**Pane 1 — Continuous compiler (watches for changes):**
```bash
latexmk -pvc main.tex
```

**Pane 2 — Editor:**
```bash
hx main.tex
```

**Pane 3 — Live PDF viewer (auto-reloads):**
```bash
zathura output/main.pdf
```

Start Pane 1 first, then Pane 3 (PDF must exist before viewer opens). Edit in Pane 2, save, and watch changes appear in Pane 3 within seconds.

## License

No license. All rights reserved.
