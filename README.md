#How to use this to install windows app on your computer

1. Open windows powershell with Admin role.
2. Click install.ps1 in this repo and click raw to get raw link
3. Run this command <p>Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('raw-url-link'))</p>

raw-url-link is the url what you got from step 2.

Then wait for the result.
