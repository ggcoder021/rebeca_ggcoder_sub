# Aurora — Simple Subscription Page

A simple, clean and modern single-file subscription page based on the Aurora project.

> Redesigned and simplified for **@GGCODER_IR**

## ✨ Features

- Single-file `index.html`
- Clean modern UI
- RTL Persian support
- English / Persian language switch
- Dark / Light mode
- Subscription information
- Used / remaining traffic
- Expiration date
- Configuration search
- Protocol filters
- Copy one or multiple configs
- Export TXT / JSON
- Subscription link copy/share
- VPN files section
- OpenVPN / WireGuard / L2TP / PPTP support
- No external CDN
- Works with Rebecca template variables

---

## 📦 Installation

### Method 1 — GitHub

1. Download or clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/Aurora-GGCODER_IR.git
```

2. Enter the folder:

```bash
cd Aurora-GGCODER_IR
```

3. Upload `index.html` to your web server.

That's it. There is no build step and no `npm install`.

---

## 🚀 Use as a Rebecca Subscription Template

This template is designed to work as a **single HTML subscription template**.

### 1. Open the file

Open:

```text
index.html
```

### 2. Copy the entire content

Copy all of the HTML code.

### 3. Add it to your Rebecca template

Create or edit your subscription template and paste the code.

### 4. Save

The page will automatically use the template variables for:

- Username
- Traffic usage
- Data limit
- Expiration
- Subscription URL
- Online users
- Last online
- VPN profiles

> Do not remove the `aurora-data` section or the template variables inside it.

---

## 🛠️ Customization

### Change the brand name

Search for:

```html
Aurora
```

### Change the footer username

Search for:

```html
@GGCODER_IR
```

### Change colors

At the top of `index.html`, edit the CSS variables:

```css
:root{
  --accent:#7c8cff;
  --accent2:#50e3c2;
}
```

### Change the title

Search for:

```html
<title>Aurora</title>
```

---

## 📁 Project Structure

```text
Aurora-GGCODER_IR/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

---

## 👤 Credits

Made and redesigned by **@GGCODER_IR**

---

## ⚠️ Disclaimer

This project is a frontend template. You are responsible for how and where you use it.
