# naqs_devices_KeysightDCSupply

## Directory structure

```text

└── naqs_devices_KeysightDCSupply/
    ├── .gitignore
    ├── pyproject.toml
    ├── README.md
    ├── LICENSE.txt
    ├── CITATION.cff
    ├── src/naqs_devices/ # note: must be same as in the parent naqs_devices repo to be in the same namespace
    │   └── KeysightDCSupply/
    │       ├── __init__.py
    │       ├── register_classes.py
    │       ├── labscript_devices.py
    │       ├── blacs_tabs.py
    │       ├── blacs_workers.py
    │       └── runviewer_parsers.py
    └── docs/
        └── index.rst

```

## How to document your device

To work within the labscript paradigm, we enforce that you write all
specification related documentation in the top-level README.md (here). Then,
any API related documentation should go in the `docs/index.rst`.
