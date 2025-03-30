# SettleUp Email Confirmation Page

This repository hosts a simple **email confirmation redirect page** for SettleUp authentication. It is deployed using **GitHub Pages** and is used to confirm user emails via Supabase.

## 🚀 How It Works

1. Supabase sends an email confirmation link containing an `access_token` and `type=signup`.
2. The user clicks the link, which opens this GitHub Pages site.
3. The page extracts the `access_token` and **redirects mobile users** to the SettleUp app via a deep link (`settleup://auth?access_token=...`).
4. If opened on a desktop browser, the page provides a manual link to open the app.

## 📂 Project Structure


