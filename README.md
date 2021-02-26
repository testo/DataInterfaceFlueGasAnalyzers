# DataInterfaceFlueGasAnalyzers
Retrieval of live values and protocols as well as transmission of measurement sites via USB/Bluetooth for testo 320 and testo 330. testo 300 offers all these features via USB as well, but only online values via Bluetooth.

## Installation
- Either download/clone entire repository and run TestoSetup.exe 
- or 
- make sure you've installed .NET Framework 4.7 and just download and run TestoDataInterfaceFlueGasAnalyzers32.msi or TestoDataInterfaceFlueGasAnalyzers64.msi.

## Change log

### v0.15
- Problem when trying to delete measurements with -RD was fixed. Be aware that trying to delete a protocol that is still active will still lead to an error.

### v0.14b
- Error message "Unknown system type occured" is now displayed without error message that text cannot be found.
- Some translations in installer were improved in various languages.
