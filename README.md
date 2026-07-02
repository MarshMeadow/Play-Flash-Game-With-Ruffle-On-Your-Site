```md
# 🎮 Play Flash Games With Ruffle On Your Site

This project lets you embed and run Flash (.swf) games on your website using **Ruffle**, a modern Flash Player emulator that replaces Adobe Flash Player.

Ruffle allows old Flash content to run safely in modern browsers without needing any Flash plugins.

---

## ⚡ What is Ruffle?

[Ruffle](https://ruffle.rs/) is an open-source Flash Player emulator written in Rust. It recreates the Flash Player environment so legacy `.swf` games and animations can still run on modern websites and browsers.

---

## 🚀 How It Works

You embed a Flash game file (`.swf`) into your website using Ruffle.

Simply replace:

```

YourFlashFileLink

````

with the direct link to your `.swf` game file.

---

## 💻 Full Example Code

Copy and paste this into your website HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Play Flash Game</title>

  <!-- Ruffle Loader -->
  <script src="https://unpkg.com/@ruffle-rs/ruffle"></script>

  <style>
    body {
      margin: 0;
      background: #0f0f0f;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: white;
      font-family: Arial, sans-serif;
    }

    .game-container {
      border: 2px solid #333;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 0 20px rgba(0,0,0,0.6);
    }
  </style>
</head>

<body>

  <div class="game-container">
    <embed
      src="YourFlashFileLink"
      width="800"
      height="600"
      type="application/x-shockwave-flash">
    </embed>
  </div>

</body>
</html>
````

---

## 🛠️ Setup Instructions

1. Upload or host your `.swf` Flash game file
2. Copy the direct URL to the file
3. Replace `YourFlashFileLink` in the code above
4. Paste the HTML into your website or embed page
5. Save and open your site in a browser

---

## 🌐 Example Usage

This method is already used on real sites for Flash game hosting:

👉 [https://sites.google.com/view/fancyexplore/shop/portal-player/fpaw1](https://sites.google.com/view/fancyexplore/shop/portal-player/fpaw1)

---

## 📱 Compatibility

* Works on modern browsers (Chrome, Edge, Firefox)
* Works on desktop and most mobile browsers
* No Flash plugin required
* Ruffle automatically emulates Flash content

---

## ⚠️ Notes

* Your `.swf` file must be publicly accessible (no login or restrictions)
* Some advanced Flash games may not work perfectly due to emulator limitations
* Performance may vary depending on game complexity
* Always use trusted `.swf` sources

---

## 🔧 Troubleshooting

**Game not loading?**

* Check if the `.swf` link is valid and publicly accessible
* Make sure the file ends in `.swf`
* Try opening the link directly in your browser

**Blank screen?**

* Some Flash features may not be supported by Ruffle
* Try a different `.swf` file

---

## 📚 Credits

* Ruffle Emulator: [https://ruffle.rs/](https://ruffle.rs/)
* Flash content belongs to original creators

---

## ❓ Support

If you need help embedding your Flash game or fixing issues, feel free to ask.

```
