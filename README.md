# Starship
Repository for Starship design

Powershell setup for Starship

Install NerdFont from nerdfonts.com
Set PowerShell profile to use NerdFont

Install via Chocolatey

> choco install starship -fy

After install open Windows Terminal

> cd .config

> code starship.toml

Verify the existence of Powershell profile
> $profile

Open $profile
> code $profile

Paste in Invoke-Expression (&starship init powershell) and save
