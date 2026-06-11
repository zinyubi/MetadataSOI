# MetadataSOI

QGIS dialog for generating SOI-aligned ISO 19115 metadata XML and maintaining the linked Excel inventory.

## Runtime dependency

Install `openpyxl` in the Python environment used by QGIS:

```bash
python -m pip install -r requirements.txt
```

The inventory workbook is read and updated exclusively through `openpyxl`; legacy ZIP/XML workbook generation is no longer used.
