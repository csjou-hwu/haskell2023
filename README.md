# haskell2023
## Ref:
### https://www.haskell.org/ghcup/
### https://www.haskell.org/ghcup/guide/
cmd
powershell
choco install haskell-dev
refreshenv
2023/6/22 Vs code suggest to install 
Set-ExecutionPolicy Bypass -Scope Process -Force;[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; try { Invoke-Command -ScriptBlock ([ScriptBlock]::Create((Invoke-WebRequest https://www.haskell.org/ghcup/sh/bootstrap-haskell.ps1 -UseBasicParsing))) -ArgumentList $true } catch { Write-Error $_ }
