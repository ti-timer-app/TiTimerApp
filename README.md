# Ti Timer — App Store pages

Static site for Ti Timer App Store metadata (marketing, support, and privacy).

## App Store Connect URLs

After enabling GitHub Pages (see below), use these URLs:

| Field | URL |
| --- | --- |
| **Support URL** (required) | `https://ti-timer-app.github.io/TiTimerApp/support.html` |
| **Marketing URL** (optional) | `https://ti-timer-app.github.io/TiTimerApp/` |
| **Privacy Policy URL** (required) | `https://ti-timer-app.github.io/TiTimerApp/privacy.html` |

**Copyright** in App Store Connect is **not a URL**. Enter plain text, for example:

```text
2026 Ti Timer
```

Apple adds the © symbol automatically.

## Enable GitHub Pages

1. Push this repository to `https://github.com/ti-timer-app/TiTimerApp`.
2. On GitHub: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **main**, folder **/ (root)**, then **Save**.
5. Wait a minute or two, then open `https://ti-timer-app.github.io/TiTimerApp/`.

## Customize

- Update the support email in `support.html` and `privacy.html` if `titimerapp@gmail.com` is not your real address.
- Adjust app features and copy in `index.html` to match the shipped app.
