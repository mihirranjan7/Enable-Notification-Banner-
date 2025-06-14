# Notification Prompt Banner

A lightweight JavaScript banner that prompts users to enable browser notifications. Built for forums, communities, and any web application where user engagement is key.

## Features

* ✅ Pure JavaScript – no frameworks or dependencies
* 🎯 Shows only to users who haven’t enabled notifications
* 🕒 Displays **once every 2 days** using `localStorage`
* 🌙 Adapts to light and dark system themes
* 📱 Mobile-friendly and minimal UI
* 🧩 Fully customizable: update text, styles, or behavior easily

## Demo

The banner displays a message like:

> “To receive notifications of chat and replies”
> \[🔔] \[×]

Once the user clicks the bell or close button, the prompt hides for 2 days.

If the user enables notifications (`Notification.permission === 'granted'`), it won’t show again.

## Installation

Include the script anywhere in your page:

```html
<script>
  // Paste the full script here
</script>
```

No additional setup required.

## Customization

* Edit the display message inside the `banner.innerHTML`
* Change timing (e.g. 2 days) by modifying `twoDays` in milliseconds
* Adjust styles directly in the inline `style` attributes
* Replace icons with your own SVG or font icons if desired

## License

MIT — free for personal and commercial use.
