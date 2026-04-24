# GitHub Upload Guide für macOS

## 1. ZIP entpacken

Entpacke die Datei und verschiebe den Ordner z. B. auf deinen Desktop.

```bash
cd ~/Desktop
```

## 2. In den Projektordner wechseln

```bash
cd credit-risk-powerbi-portfolio
```

## 3. Prüfen, ob Git installiert ist

```bash
git --version
```

Falls Git fehlt:

```bash
xcode-select --install
```

## 4. Git Repository initialisieren

```bash
git init
```

## 5. Dateien hinzufügen

```bash
git add .
```

## 6. Ersten Commit erstellen

```bash
git commit -m "Initial commit: credit risk Power BI portfolio project"
```

## 7. Neues GitHub Repository erstellen

Erstelle auf GitHub ein neues Repository, z. B.:

```text
credit-risk-powerbi-portfolio
```

Wichtig: Kein README auf GitHub erzeugen, da dieses Projekt bereits ein README enthält.

## 8. Remote Repository verbinden

Ersetze `DEIN-USERNAME` durch deinen GitHub-Namen:

```bash
git remote add origin https://github.com/DEIN-USERNAME/credit-risk-powerbi-portfolio.git
```

## 9. Branch umbenennen

```bash
git branch -M main
```

## 10. Projekt hochladen

```bash
git push -u origin main
```

## 11. Screenshots ergänzen

Öffne die `.pbix` Datei in Power BI, exportiere Screenshots und speichere sie in:

```text
images/
```

Danach erneut hochladen:

```bash
git add images/
git commit -m "Add dashboard screenshots"
git push
```

## Hinweis zu großen Power-BI-Dateien

GitHub erlaubt normale Dateien bis 100 MB. Falls deine `.pbix` später größer wird, nutze Git LFS:

```bash
brew install git-lfs
git lfs install
git lfs track "*.pbix"
git add .gitattributes
git commit -m "Track Power BI files with Git LFS"
```
