# WtImpExpPsd1-Cl

### STATUS
Development. The principles are...
- focus on, competence and reliability and efficiency, but do not introduce "security".
- ensure the cmdlets work for, "PowerShell Core 7" and "Powershell 5.1", ensure everything is compatible.
- we ideally want them to work more, competently and faster, than the PowerShell/PowerShellCore versions of the relating cmdlets.
- we want them to utilize exactly the same, syntax and usage, for import, and a fitting theme of, syntax and usage, for the export, compared to the powershell import. 

## DESCRIPTION
Powershell and PowerShellCore do not have an Export-PowerShellDataFile cmdlet, GPT4 typically insists there is "GPT: The statement is false. Both PowerShell and PowerShell Core do include the Export-PowerShellDataFile cmdlet.", therein, every time the given user attemts to use a Psd1 with a script created in GPT4, then this will happen, wasting multiple frustrating interactions, hence, I wanted to solve that issue, and not only that, fix the issue of incorrectly reading/writing to PSD1's with quality, import and export, cmdlets, I can rely upon and are efficient, hence, "Wiseman-Timelord's Import Export Psd1" cmdlets were created for exactly this purpose. 

### DEMONSTRATION
- Some GPT4 logic upon exporting Psd1 files (in a new session)...
```
WT:
Powershell and PowerShellCore do not have an Export-PowerShellDataFile cmdlet, is this, true or false?

GPT4:
The statement is false. Both PowerShell and PowerShell Core do include the `Export-PowerShellDataFile` cmdlet.
```
- Standard Psd1 import has issues...
```
WT:
Please tell me about the, limitations and issues, of Import-PowerShellDataFile.

GPT4: 
Formatting Errors: The most common issue arises from improperly formatted .psd1 files. If the syntax within the file is not correct, the cmdlet will fail to parse the data.
Incorrect Path: Issues can arise if the file path is incorrect or inaccessible due to permission restrictions.
Handling Complex Data: While it can import nested hashtables or custom objects, the complexity of the data structure can lead to confusion or errors in interpretation.
Character Encoding: If the file’s character encoding is not compatible with PowerShell’s expected encoding, it may lead to errors or incorrect data import.
```

## USAGE
- There will be an ingenious batch installer, they will be in a module.
- The import will work the same.
- The export will work as one would logically expect.


