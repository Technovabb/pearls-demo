# Pearls Parent Portal: demo

An interactive concept demo of a parent app for **Pearls Dance Academy**, made by **Tech Nova Barbados**.

**Live:** https://technovabb.com/pearls-demo/

It's a clickable demo: the login, payments and data are samples, and nothing is sent or charged.

## Screens
- **Log in:** parent, plus staff/teacher.
- **Home:** the child's progress, balance due, next class and the latest teacher note.
- **Progress and skills:** levels, plus skills learned, being learned, and coming up.
- **Lessons:** practise-at-home lessons with a player.
- **Pay:** tuition checkout and a payment-received screen.
- **Teacher view** and a **certificate**.

## Install it on a phone, like an app
- **iPhone (Safari):**
  1. Open the link.
  2. Tap **Share**, then **Add to Home Screen**, then **Add**.
- **Android (Chrome):**
  1. Open the link.
  2. Tap **Install** when it pops up, or tap the **⋮** menu and choose **Install app**.

It then opens full-screen with the Pearls icon. After the first visit it also works with no internet, which is useful for showing it in a meeting.

## Files
- `index.html` is the whole demo (screens, styles and script).
- `manifest.webmanifest` holds the app name, colours and icons. The icons are in `icons/`.
- `sw.js` makes the app installable and lets it work offline. Pages load fresh whenever there's a connection.

GitHub Pages publishes the `main` branch. Changes are live about a minute after you push.
