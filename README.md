# Toggle Button Redirect

This is a simple HTML/CSS/JavaScript toggle switch component that **redirects users to different pages** based on its state.

## 🚀 Features

- Clean and responsive toggle UI
- Smooth animation using pure CSS
- JavaScript logic for conditional redirection
- Easy to customize for your own URLs

## 💡 How It Works

- When the toggle switch is turned **on**, the user is redirected to `Page 1`.
- When it's turned **off**, the user is redirected to `Page 2`.
- Redirection happens after a 1-second delay to provide feedback.

## 🔧 Customization

Update the URLs in the script section to your desired pages:

```javascript
window.location.href = "https://example.com/page1"; // for ON
window.location.href = "https://example.com/page2"; // for OFF
