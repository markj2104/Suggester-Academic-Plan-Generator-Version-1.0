# Suggested Academic Plan visualizer

A Python learning project that reads course-plan JSON and renders four-year academic-plan diagrams with Matplotlib.

## Run

Use Python 3 in a virtual environment, then run from the repository folder:

```sh
python -m pip install -r requirements.txt
python main.py
```

The script reads `IT-SAP.json`, `Cybersecurity-SAP.json`, and `CRIMJ-SAP.json` in that order. Close each plot to continue to the next one. To use different files, edit `json_filenames` in `main.py` and preserve the supplied JSON schema.

## Scope

This visualizes supplied plans; it does not generate schedules, validate prerequisites, or check current degree requirements. The 2023 sample data is historical, not academic advising. A graphical desktop is required to display the plots. Century Gothic is optional; Matplotlib may use a fallback font.
