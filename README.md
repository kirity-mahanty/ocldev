# ocldev
Development library for working with OCL metadata and APIs

`ocldev` package is published to PyPi, which means you can easily install it with pip, eg:
```
pip install ocldev
```

These classes are implemented currently:
* OclResourceList, OclCsvResourceList, OclJsonResourceList - 
* OclFlexImporter & OclBulkImporter - Used to import JSON resources into OCL
* OclImportResults - Used to process the results of an import
* OclExport & OclExportFactory - Used to fetch exports from OCL
* OclCsvToJsonConverter - Used to convert CSV files to OCL-formatted JSON
* OclValidator - Validates OCL-formatted JSON and CSV resources and resource lists
