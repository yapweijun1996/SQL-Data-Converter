# SQL Insert Viewer

**SQL Insert Viewer** is a simple web-based tool that lets you paste SQL `INSERT INTO` statements and instantly see the data in a readable table format.

## 🚀 Features

- Parses standard `INSERT INTO ... VALUES (...)` SQL statements
- Displays data in a clean HTML table
- Shows the length of each value
- Highlights date formats like `{d 'YYYY-MM-DD'}` automatically

## 🧑‍💻 How to Use

1. Open `index.html` in your browser.
2. Paste your SQL `INSERT INTO` statement into the textarea.
3. Click **Convert**.
4. View the results in table format below.

## 📁 Files

- `index.html` – Main HTML file with embedded JavaScript and styles

## 💡 Example

```sql
INSERT INTO users (name, birthdate, note)
VALUES ('Alice', {d '1990-01-01'}, 'Test user');
````

## 📜 License

This project is open-source and free to use.

