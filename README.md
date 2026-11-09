# AfriStream

**Multi-platform live streaming dashboard + Tanzanian mobile money payments**

Looks and feels like modern tools such as Gyre.pro, but focused on:

- Streaming to TikTok, Instagram, YouTube, Facebook, Twitch, Kick, X at the same time
- Unified comment inbox with quick reply
- Per-platform settings
- Tips & donations to **Vodacom M-Pesa, Yas (Tigo), Airtel Money, Halotel, TTCL, Azania Bank**

## Important reality check

This is a **beautiful static front-end / control panel**.

| What it does | What it does **not** do |
|--------------|-------------------------|
| Professional Gyre-style UI | Actual video encoding / RTMP relay |
| Platform cards & status | Real-time connection to TikTok/Instagram APIs |
| Comment inbox mock + reply UI | Automatic view boosting (not supported) |
| Payment settings for M-Pesa etc. | Direct interception of platform payouts |

### To actually multi-stream
1. Use **OBS Studio** + multi-RTMP plugin, **or**
2. Run an open-source restreamer on a cheap VPS (Prism, Restreamer, xplex, etc.)
3. Point this dashboard at your stream status / keys

### To receive real M-Pesa / Yas / Airtel tips
- Use a licensed payment gateway: **IntaSend**, **PlusPesa**, Flutterwave, etc.
- Or simply show your number + USSD instructions on the stream overlay

## Deploy free on GitHub Pages

1. Create a new public GitHub repository
2. Upload the contents of this folder (`index.html` + `README.md`)
3. Go to **Settings → Pages**
4. Source: Deploy from branch → `main` → `/ (root)`
5. Your site will be live at `https://yourusername.github.io/repo-name`

## Local preview

Just open `index.html` in any browser.

---

Built for creators in Tanzania and East Africa.
