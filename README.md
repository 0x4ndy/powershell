# powershell

## Start-up

Firs, you need to make sure that you are able to execute scripts by changing the **Windows Execution Policy**. This will let you configure the `$profile` file (described later), as well as all other scripts you may want to create.

```powershell
Set-Execution-Policy -ExecutionPolicy Unrestricted -Scope CurrentUser
```

To run PowerShell commands on every start of a PowerShell, edit the following file:

```powershell
echo $profile
```

This file is an equivalent of `.bashrc`.

Basic setup:

```
Set-Alias ll ls
```
