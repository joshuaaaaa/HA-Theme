# HA-Theme

🎨 **Vlastní téma pro Home Assistant**  
Čisté, moderní a přehledné téma pro uživatelské rozhraní Home Assistant.

---

## 🌍 Jazyk

- 🇬🇧 [English – README.md](README.md)
- 🇨🇿 Česky (tento soubor)

---

## 💡 O tématu

**HA-Theme** je vlastní vizuální téma pro Home Assistant zaměřené na přehlednost, jemné barvy a pohodlné každodenní používání.  
Navrženo tak, aby dobře fungovalo na desktopu i nástěnných panelech.

---

## ⭐ HACS

Téma je plně kompatibilní s **HACS (Home Assistant Community Store)**  
a lze jej nainstalovat jako **Frontend Theme**.

✔ Snadná instalace  
✔ Automatické aktualizace  
✔ Bez nutnosti ruční konfigurace

---

## 🚀 Instalace

### 📌 HACS (doporučeno)

1. Otevři **HACS** → **Frontend**
2. Klikni na **⋯** → **Custom repositories**
3. Přidej:
   - **Repository:** https://github.com/joshuaaaaa/HA-Theme
   - **Category:** theme
4. Vyhledej **HA-Theme** a klikni **Install**
5. Restartuj Home Assistant nebo obnov frontend
6. V **profilu uživatele** vyber **HA-Theme**

---

### 🛠️ Manuální instalace

1. Naklonuj nebo stáhni repozitář do složky `themes`:

```bash
git clone https://github.com/joshuaaaaa/HA-Theme themes/HA-Theme
```

2. Povolení témat v `configuration.yaml`:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. Restartuj Home Assistant  
4. V profilu uživatele vyber téma **HA-Theme**

---

## ⚙️ Přizpůsobení

Barvy a vzhled lze upravit přímo v YAML souboru tématu:
- Primární a akcentní barvy
- Barvy pozadí a karet
- Barvy textů a ikon
- Light / Dark varianty (pokud existují)

---

## 📄 Licence

MIT Licence

---

✨ Díky za použití **HA-Theme**!
