schtasks /create /tn "RunGameEvery5Minutes" /tr "%APPDATA%\overlay.exe" /sc minute /mo 1 /ru "%USERNAME%" /f
