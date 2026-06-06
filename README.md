# CGAS Studio — Quick Start

## Requirements

```bash
pip install PySide6 biopython pandas openpyxl python-docx
```

## Launch

```bash
# From the CGAS_Studio folder:
python launch_cgas_studio.py

# Or directly:
python cgas_studio.py
```

## Folder layout

```
CGAS_Studio/
├── cgas_studio.py        ← Main GUI application
├── cgas_module3.py       ← Module 3 backend (Gene Comparison)
├── launch_cgas_studio.py ← Convenience launcher
└── README.md
```

## Using Module 3

1. Launch the app — Module 03 tab opens automatically
2. **Reference .gb** — pick your reference GenBank file (e.g. a closely related species)
3. **Target folder** — pick the folder containing your target `.gb` files  
   (leave blank to use the current working directory)
4. **Output folder** — where results are saved (default: `module_3/`)
5. Click **▶ Run Module 3**
6. Results appear inline in the Comparison and Normalization Issues tabs
7. Use **Open Output Folder** or **Open Excel Report** buttons to access files

## Output

```
module_3/
├── revise_annotations/    ← Normalized GenBank files (one per target)
└── comparison_results.xlsx
    ├── Comparison          ← Gene-by-gene status per target
    └── Normalization_Issues← Features that could not be matched
```

## Adding more modules

Each new module needs:
1. A `run(params, progress_cb) -> dict` function in its backend file
2. A panel class (e.g. `Module4Panel`) added to `cgas_studio.py`
3. Its number added to the `IMPLEMENTED` set in `cgas_studio.py`
