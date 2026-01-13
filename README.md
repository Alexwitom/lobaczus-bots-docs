# 🤖 Lobaczus Bot’s
## 📘 Official Documentation

Welcome to **Lobaczus Bot’s** — a **premium automation solution** with:  
🔐 License protection  
🧬 HWID binding  
🛒 Multi‑shop integrations  

This documentation is:
- 💼 Professional  
- 🧠 Beginner‑proof  
- 📖 Clear  
- 🎫 Support‑ticket‑saving  

---

## 📦 Installation & Launcher

### 🛠 Installation steps
1. ⬇️ Download the official installer  
2. 🛡 Run installer as **Administrator**  
3. ✅ Finish installation  
4. 🚀 Launch **Lobaczus Launcher**

The launcher manages:
- 🤖 bots  
- ⚙️ configuration  
- 🔐 licenses  
- 🔄 updates  

---

## 🚀 First Launch

On first launch:
- 🔑 log in using your **license key**
- 🌐 license is validated **server‑side**
- 🧬 **HWID is assigned automatically**

❌ Without a valid license, bots will **NOT** start.

---

## ⚙️ Global Configuration

All configuration is managed inside the **Launcher UI**.

💾 Save Configuration:
- shows confirmation modal
- restarts the app

🛒 Save Shop Configuration:
- shows toast only
- no restart

ℹ️ This behavior is **intentional**.

---

## 🧾 Environment File

📍 Location:
%APPDATA%/LobaczusBots/env.json

---

## 🛒 Shop Overview

Supported shops:
- 🟢 Shopify  
- 🟣 SellHub  
- 🔵 WooCommerce  

⛔ Bot will **NOT** start if no shop is verified.

---

## 🟢 Shopify (Backend Managed)

✔ Fully backend‑controlled  
✔ No manual credentials  
✔ Theme & embed colors synced automatically  

🚫 DO NOT MODIFY

SHOP:  
enabled: true  
storeType: shopify  
clientId: your-client-id  
shop: your-shop.myshopify.com  

THEME_COLOR: #EC4899  
DISCORD_EMBED_COLOR: #7C3AED  

📊 Status:
SHOP: Shopify

---

## 🟣 SellHub

### 🔐 Required
- Webhook Secret  

SHOP:  
enabled: true  
storeType: sellhub  
webhookSecret: YOUR_SECRET  

THEME_COLOR: #6D28D9  
DISCORD_EMBED_COLOR: #7C3AED  

---

## 🔵 WooCommerce

### 🔑 Required
- Store URL  
- Consumer Key  
- Consumer Secret  

SHOP:  
enabled: true  
storeType: woocommerce  
storeUrl: https://yourstore.com  
consumerKey: ck_xxxxx  
consumerSecret: cs_xxxxx  

THEME_COLOR: #6D28D9  
DISCORD_EMBED_COLOR: #7C3AED  

---

## 📊 Bot Status

Displayed:
- 🔐 License status  
- 🛒 Shop status  
- ⏱ Expiration time  

Shop rules:
❌ SHOP: NOT VERIFIED → bot blocked  
✅ SHOP: Shopify / SellHub / Woo → bot allowed  

---

## ⏱ License Expiration Format

Format:
📅 Days + ⏰ Hours  

✅ Correct:
2 days 8 hours  

❌ Never allowed:
2 days 0 hours  

---

## 🔐 License & HWID

- 🌐 License stored server‑side  
- 🧬 HWID binding enabled  
- 🖥 Backend required  

🚫 Cracked or modified builds will **NOT** work.

---

## ♻️ Reset All Bot Configuration

📍 Location:
Launcher → Settings  

🔴 Button:
RESET ALL BOT CONFIGURATION  

This will:
- 🧹 remove all bot configs  
- 🗑 clear %APPDATA%/LobaczusBots  
- 🔄 reset launcher state  

⚠️ This action is **IRREVERSIBLE**.

---

## 🧹 Uninstall & Cleanup

Removes:
- ❌ Launcher  
- ❌ Electron app  
- ❌ Bot data  
- ❌ %APPDATA%/LobaczusBots  

---

## ❓ FAQ

❓ Run without backend?  
➡️ No.

❓ Change HWID manually?  
➡️ No, support only.

❓ Manual Shopify config?  
➡️ No, backend only.

---

© 🖤 Lobaczus Bot’s — All rights reserved.
