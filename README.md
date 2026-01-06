# Xat Intel·ligent - GitHub Pages

Un xat funcional amb intel·ligència artificial que pots incrustar a qualsevol web.

## 🚀 Com publicar-ho a GitHub Pages

### Pas 1: Crear el repositori a GitHub

1. Ves a [GitHub](https://github.com) i inicia sessió
2. Clica el botó **"New"** per crear un nou repositori
3. Posa-li un nom, per exemple: `chat-intel·ligent` o `ai-chat`
4. Marca'l com a **Public**
5. **NO** marquis "Add a README file"
6. Clica **"Create repository"**

### Pas 2: Pujar els arxius

**Opció A: Des de la interfície web de GitHub (més fàcil)**

1. Al teu nou repositori, clica **"uploading an existing file"**
2. Arrossega l'arxiu `index.html` 
3. Escriu un missatge de commit: "Afegir xat inicial"
4. Clica **"Commit changes"**

**Opció B: Des de la línia de comandes**

```bash
# Navega a la carpeta on tens l'arxiu
cd ruta/a/la/carpeta

# Inicialitza git
git init

# Afegeix els arxius
git add index.html

# Fes el commit
git commit -m "Afegir xat inicial"

# Connecta amb el teu repositori (substitueix amb la teva URL)
git remote add origin https://github.com/EL-TEU-USUARI/EL-TEU-REPO.git

# Puja els arxius
git branch -M main
git push -u origin main
```

### Pas 3: Activar GitHub Pages

1. Al teu repositori, ves a **Settings** (configuració)
2. Al menú lateral, clica **Pages**
3. A "Source", selecciona **main** branch
4. Clica **Save**
5. Espera 1-2 minuts

### Pas 4: Accedir al teu xat

La teva URL serà:
```
https://EL-TEU-USUARI.github.io/EL-TEU-REPO/
```

Per exemple: `https://marc.github.io/chat-intelligent/`

## 📦 Incrustar a la teva web

Un cop publicat, pots incrustar-lo a qualsevol pàgina HTML amb un iframe:

```html
<iframe 
  src="https://EL-TEU-USUARI.github.io/EL-TEU-REPO/" 
  width="100%" 
  height="700px" 
  frameborder="0"
  style="border: none; border-radius: 10px;"
></iframe>
```

## 🎨 Personalitzar

Pots editar l'arxiu `index.html` per canviar:

- **Colors**: Modifica els valors de `background`, `color` als estils
- **Missatge inicial**: Canvia el primer missatge a l'array `messages`
- **Idioma**: Canvia els textos en català per altres idiomes
- **Mida**: Modifica `height: '500px'` al contenidor de missatges

## 🔧 Actualitzar el xat

Per fer canvis després de publicar:

1. Edita l'arxiu `index.html` 
2. Puja els canvis a GitHub (commit + push)
3. Espera 1-2 minuts i els canvis es veuran reflectits

## 📱 Responsive

El xat s'adapta automàticament a mòbils, tauletes i ordinadors.

## ⚠️ Notes importants

- L'API d'Anthropic està integrada sense necessitat de claus API addicionals
- El xat funciona directament des del navegador
- És completament gratuït amb GitHub Pages
- GitHub Pages és públic, no hi pugis informació sensible

## 💡 Exemple d'ús

Perfet per:
- Webs personals
- Portfolios
- Projectes educatius
- Demostracions de productes
- Assistència al client

## 🆘 Ajuda

Si tens problemes:
1. Verifica que el repositori és públic
2. Comprova que GitHub Pages està activat
3. Espera uns minuts després d'activar-lo
4. Refresca la pàgina amb Ctrl+F5

---

Creat amb React i Claude AI ❤️
