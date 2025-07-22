```markdown
# 🎮 Game Discount Notifier - Chrome Extension

A **Chrome Extension** that keeps gamers updated with **heavy discounts (50% and above)** on their favorite games across **multiple platforms** like **Steam, Epic Games, Ubisoft, Riot**, and more. No logins. No clutter. Just clean, powerful notifications when the deals drop.

---

## 🚀 Why This Project?

In a world with multiple gaming platforms, the **same game is often available on different sites with different prices**. Gamers either lose out on massive deals or spend time manually checking platforms for discounts.

This extension **solves that problem** by:
- Letting users track specific games.
- Monitoring major platforms.
- Notifying users when **any platform offers 50%+ discount**.
- Selecting **the platform with the best deal or longest duration** if multiple are available.

---

## 🕹 Real-World Example

Imagine you're waiting to buy **FIFA 25**. Here's what happens:
- You open the extension.
- Add "FIFA 25" to your watchlist.
- The extension runs price checks every few hours.
- **Steam** has a 60% discount → You instantly get a notification!
- You click → Directs to the Steam page → Game is yours at a deal 🔥

Now imagine it was **only 50% off on Steam** but **Epic Games has 55%** — the extension picks Epic Games and sends you the link.

If both platforms have **same discount**, it picks the one with **longer validity**, so you don’t miss it.

---

## 📦 Features

✅ Track games across platforms  
✅ Get notified only when discount is **≥ 50%**  
✅ Smart platform selection based on **best deal**  
✅ Lightweight — no login, no signup  
✅ Works in background — auto-checks regularly  
✅ Manually refresh anytime  

---

## 🧠 Tech Stack

| Tech         | Purpose                                  |
|--------------|------------------------------------------|
| JavaScript   | Core logic and Chrome APIs               |
| HTML/CSS     | UI design for popup                      |
| Chrome API   | Extension lifecycle, alarms, notifications |
| Cheerio.js   | Web scraping deals (free, fast)          |
| Fetch API    | Hitting public APIs or scraping pages    |
| LocalStorage | Storing wishlisted games                 |

---

## 🛠 Architecture

```

User adds game ➜ Extension saves in LocalStorage ➜
Periodic background check (scraper/API) ➜
Compares discounts across platforms ➜
Applies smart rules (highest %, longest validity) ➜
Sends notification ➜ User clicks to go to deal

```

---

## 🏗 How to Run Locally

1. **Clone this repo**  
```

git clone [https://github.com/your-username/game-discount-notifier.git](https://github.com/your-username/game-discount-notifier.git)

```

2. **Go to Chrome > Extensions > Enable Developer Mode**

3. **Click “Load Unpacked” and select the project folder**

4. Done! 🎉 Use the extension from the toolbar.

---

## 💡 Future Improvements

- Add notification history/log  
- Let users choose discount threshold (e.g., 70%)  
- Add sound alerts  
- Track deal expiry timer  
- Add support for currency conversion  

---

## 🌐 Supported Platforms

- Steam  
- Epic Games  
- Ubisoft  
- Riot (in future)  
- GOG (planned)  
- Microsoft Store (planned)

---

## 📜 License

MIT License. Free to use and contribute.

---

## 🤝 Contributing

Have ideas? Want to improve scrapers? Feel free to fork and raise a PR!  
Let’s help gamers never miss a deal again.

---

## 👨‍💻 Creator

**Manas Shinde**  
Solving real-world gamer problems, one extension at a time.

---

```
