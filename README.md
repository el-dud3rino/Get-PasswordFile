# Get-PasswordFile
Stolen from https://www.auditscripts.com/extracting-windows-passwords-powershell/

.SYNOPSIS 
  
    Copies either the SAM or NTDS.dit and system files to a specified directory. 
  
.PARAMETER DestinationPath 
  
    Specifies the directory to the location where the password files are to be copied. 
  
.OUTPUTS 
  
    None or an object representing the copied items. 
  
.EXAMPLE 
  
    Get-PasswordFile "c:\temp"
