# Automatizovaný test kontaktního formuláře pomocí Playwrightu

## Spuštění testu na desktopu

nainstalujte node modules pomocí příkazu

```powershell
> npm install
```

### Spuštění testu jedenkrát

Pro prohlížeč chromium spustím test následovně:

```powershell
> npx playwright test --project chromium
```

### Spuštění testu vícekrát

Pro opakované spuštění testu slouží skript sur-contact.sh. Spustíte ho v terminálu Git Bash (mezi Powershell a Git Bash terminálem se dá přepínat v liště terminálu vpravo) následovně:

```bash
$ bash run-contact.sh
```
