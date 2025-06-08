# Summary-textarea
# 📝 Character Counter Web App

This is a simple HTML + JavaScript web app that allows users to type a message in a text area with a real-time character counter. It displays how many characters have been typed and how many are remaining, with a maximum limit of 200 characters.

## 🔧 Features

- Live character counter
- Displays:
  - `Characters Typed: X/200`
  - `Remaining: Y/200`
- Prevents typing beyond 200 characters
- Shows a red warning message when the character limit is reached

## 📱 Responsive

While this version is not fully responsive, you can easily enhance it by wrapping the layout with media queries.

## 📜 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## 🔒 Character Limit Logic

- Maximum allowed characters: **200**
- Input is automatically trimmed if the user exceeds the limit.
- Warning appears once the limit is reached.

## 🧪 Sample Behavior

| Action            | Output                          |
|-------------------|----------------------------------|
| Typed 150 chars    | Characters Typed: 150/200       |
|                   | Remaining: 50/200                |
| Typed 200 chars    | Warning displayed: "⚠️ Character limit reached!" |
| Typed >200 chars   | Extra characters trimmed         |

## 🔗 Links

- 🔗 GitHub Repo: [Character Counter](https://github.com/YOUR_USERNAME/character-counter)
- 🌐 Live Demo: [View Demo](https://YOUR_USERNAME.github.io/character-counter/)
