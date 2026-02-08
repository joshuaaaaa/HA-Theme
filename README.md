# HA-Theme

<img width="1352" height="449" alt="image" src="https://github.com/user-attachments/assets/4c1a5932-1f70-4078-9ac2-74b9a7187568" />

🎨 **Custom Home Assistant Theme**  
Clean, modern and readable theme for Home Assistant UI.

---

## 🌍 Language

- 🇬🇧 English (this file)
- 🇨🇿 [Česky – README_CZ.md](README_CZ.md)

---

## 💡 About

**HA-Theme** is a custom Home Assistant theme focused on a clean layout, soft colors and good readability for everyday use.  
Designed to look good on both desktop and wall-mounted dashboards.

---

## ⭐ HACS

This theme is fully compatible with **HACS (Home Assistant Community Store)**  
and can be installed as a **Frontend Theme**.

✔ Easy installation  
✔ Automatic updates  
✔ No manual configuration required

---

## 🚀 Installation

### 📌 HACS (recommended)

1. Open **HACS** → **Frontend**
2. Click **⋯** → **Custom repositories**
3. Add:
   - **Repository:** https://github.com/joshuaaaaa/HA-Theme
   - **Category:** theme
4. Search for **HA-Theme** and click **Install**
5. Restart Home Assistant or reload frontend
6. Go to **User Profile** → **Themes** → select **HA-Theme**

---

### 🛠️ Manual installation

1. Clone or download the repository into your `themes` directory:

```bash
git clone https://github.com/joshuaaaaa/HA-Theme themes/HA-Theme
```

2. Enable themes in `configuration.yaml`:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. Restart Home Assistant  
4. Select **HA-Theme** in your user profile

---

## ⚙️ Customization

You can customize colors and appearance directly in the theme YAML file:
- Primary and accent colors
- Background and card colors
- Text and icon colors
- Light / Dark variants (if available)

---

## 📄 License

MIT License

---

✨ Thanks for using **HA-Theme**!
