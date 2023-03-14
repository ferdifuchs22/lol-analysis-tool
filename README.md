# lol-analysis-tool
Visual Analytics Tool zur Vor- und Nachbereitung für Casual League of Legends Spieler auf Basis von Match-Daten

Anleitung zum lokalen Ausführen der Anwendung:
    1. lol-analysis-tool Ordner im Terminal öffnen 
    
    2. Notwendigen Packages installieren:
        pip install -r requirements.txt

    3. In den ".streamlit" Ordner wechseln und Datei namens "secrets.toml" anlegen
        3.1 In die erste Zeile der Datei API Key als String folgendermaßen hinterlegen: 
            api_key = "RGAPI-*********-****-****-****-************"

    4. Zurück in lol-analysis-tool Ordner wechseln und streamlit Anwendung folgendermaßen starten:
        python -m streamlit run .\login.py
