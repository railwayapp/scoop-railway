# scoop-railway

The official Scoop bucket for installing the Railway CLI. All binaries are signed using the `Secure Hashing Algorithm` algorithm.

## Install Railway CLI

This presumes you have Scoop installed, if you don't, see [this](#install-scoop)

```ps1
scoop bucket add railway https://github.com/railwayapp/scoop-railway; scoop install railway/railway
```

## Updating

Simply type `scoop update railway/railway` to update your installation of the CLI.

## Install Scoop

Step by step instructions for installing Scoop.

1. Open PowerShell
2. Type the following commands into PowerShell: `iwr -useb get.scoop.sh | iex;`
3. Validate that Scoop is working by typing `scoop`. If it errors, and says something about execution policies, please see [this](#execution-policy) to fix it.

## Execution Policy

To fix any execution policy errors you may get, open an administrative instance of PowerShell and type this to allow Scoop and the apps it installs to run.

```ps1
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
```