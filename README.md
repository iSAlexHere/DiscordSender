
# 🎉 DiscordSender Web Interface 🎉

![HTML Badge](https://img.shields.io/badge/HTML-5-orange?style=flat&logo=html5) ![CSS Badge](https://img.shields.io/badge/CSS-3-blue?style=flat&logo=css3)

Welcome to the **DiscordSender** project! This repository features a simple and intuitive web interface for sending messages to a Discord server using webhooks.

## ✨ Features

- 💻 **HTML/CSS Web Interface** – Clean and minimal design for user interaction.
- 🔗 **Discord Webhook Integration** – Easily send messages to a Discord server.
- ⚡ **Real-Time Messaging** – Send messages instantly to your server through webhooks.
- 🌐 **Customizable** – Tweak it as per your project needs with ease!

## 🚀 How It Works

The `index.html` in this repository provides a basic form that allows users to send messages to a specified Discord webhook. Once you provide a valid Discord Webhook URL and type your message, it sends the message directly to the connected Discord channel.

## 🛠️ Setup and Usage

1. **Clone the Repository**
    ```bash
    git clone https://github.com/iSAlexHere/DiscordSender.git
    ```
2. **Open `index.html` in your browser**
    - You can directly open the `index.html` file on any modern browser.
3. **Enter Webhook URL and Message**
    - Input the Discord Webhook URL.
    - Type your message and hit **Send**! 🚀

## 📋 Code Overview

```html
<form action="https://discord.com/api/webhooks/WEBHOOK_ID/WEBHOOK_TOKEN" method="POST">
    <input type="text" name="content" placeholder="Type your message" required>
    <button type="submit">Send</button>
</form>
```

- The form posts the message directly to your Discord webhook URL.
- It requires **content** (message) to be filled, and then sends the data to the webhook using the **POST** method.

## 💡 Customization

- You can change the form to include additional fields or buttons.
- Modify the appearance of the form with **CSS** by adjusting the styles in the `<style>` tag within the `index.html` file.

## 📦 Technologies Used

- 🖥️ **HTML5** for structure
- 🎨 **CSS3** for styling
- 🔗 **Discord Webhooks** for integration

## 📄 License

This project is licensed under the MIT License. Feel free to use, modify, and distribute this project.
