# SignatureStealer

Sig Steal is a tool that steals a signature from a file and copy it to whathever file you want.
Beyond Stealing, Sig Steal goes a step further by Windows Internal to trick the system to treat the copied signature as valid.

Obs: We can only clone a x32 binary to x32 , and x64 binary to x64
use the sysInternals tool `sigcheck` to verify the signature and the format of the file

> [!WARNING]
> Please Compile using Visual Studio 2022 Pro with All Packages!!!

# Usage
```
sigsteal.exe GoogleChrome.exe fakeFile.exe
```

# Usage
```
sigsteal.exe kernel32.dll fakeDll.dll
```

## Compiling PowerShell to .EXE
Obs2: To compile a powershell .ps1 to .exe we use the below command from `ps2exe` suite
```
ps2exe -x64 -inputFile .\script.ps1 -outputFile .\script.exe
```
