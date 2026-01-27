# gBadminton App - Privacy & Support Pages

Disse HTML-filene brukes for gBadminton iOS/macOS app.

## 📝 Neste steg

### 1. Opprett GitHub Repository

1. Gå til https://github.com/new
2. Repository name: `gbadminton-pages`
3. Description: "Privacy Policy and Support pages for gBadminton app"
4. **Public** ✅ (må være public for GitHub Pages)
5. **IKKE** initialize with README (vi har allerede filer)
6. Trykk "Create repository"

### 2. Push til GitHub

Erstatt `DITT-GITHUB-BRUKERNAVN` med ditt faktiske brukernavn:

```bash
cd /Users/geirlapstuen/gbadminton-pages
git remote add origin https://github.com/DITT-GITHUB-BRUKERNAVN/gbadminton-pages.git
git branch -M main
git push -u origin main
```

### 3. Aktiver GitHub Pages

1. Gå til repository på GitHub
2. Klikk **Settings** (øverst)
3. Scroll ned til **Pages** (venstre meny)
4. Under "Source":
   - Branch: `main`
   - Folder: `/ (root)`
5. Klikk **Save**
6. Vent 2-3 minutter

### 4. Dine URLer

Etter GitHub Pages er aktivert:

- **Privacy Policy:** `https://DITT-GITHUB-BRUKERNAVN.github.io/gbadminton-pages/privacy-policy.html`
- **Support:** `https://DITT-GITHUB-BRUKERNAVN.github.io/gbadminton-pages/support.html`

### 5. Bruk i App Store Connect

Når du submitter gBadminton til App Store:

1. **Privacy Policy URL:** Paste URL fra over
2. **Support URL:** Paste support URL fra over
3. **Marketing URL:** (valgfritt) Kan også bruke support URL

---

## 📂 Filer i dette repoet

- `privacy-policy.html` - Privacy Policy for gBadminton
- `support.html` - Support & FAQ page
- `README.md` - Denne filen

## ✅ Husk

Disse filene må være **public** (åpent tilgjengelig) for at Apple kan verifisere dem under App Review.
