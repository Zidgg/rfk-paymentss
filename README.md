# Kape't Bahay sa RFK — Payment Page

A simple, static "scan to pay" page for Kape't Bahay sa RFK, built with plain HTML/CSS
(no build step, no dependencies) so it can be hosted for free on GitHub Pages.

## Files

```
index.html            the page
style.css              all styling
assets/
  cafe-logo.jpg         cafe logo (hero)
  qr-payment.png         payment QR code
  tapcard-logo.png       "Powered by Tap Card" mark
```

## Updating the QR code later

Replace `assets/qr-payment.png` with a new image of the same file name, keep the
image reasonably square, and the page will pick it up automatically — no code
changes needed.
