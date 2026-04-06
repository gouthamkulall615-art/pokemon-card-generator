# 🎴 Pokémon Card Generator

A sleek, interactive web app that generates dynamic Pokémon cards using the [PokéAPI](https://pokeapi.co/). Search any Pokémon and instantly view its stats, types, abilities, and artwork in a beautifully styled card.



---

## ✨ Features

- 🔍 Search any Pokémon by name or ID
- 🃏 Dynamically generated card with official artwork
- 📊 Displays base stats, type, height, weight & abilities
- 🎨 Type-based dynamic color theming on each card
- ⚡ Fast and responsive — works on mobile & desktop
- 🌐 Powered by the free [PokéAPI](https://pokeapi.co/)

---

## 🖼️ Preview

![Pokémon Card Generator Demo](demo-img.jpg)

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling & animations |
| JavaScript (Vanilla) | Logic & API calls |
| PokéAPI | Pokémon data source |
| Vercel | Deployment |

---

## 🚀 Getting Started

### Prerequisites
Just a modern web browser — no installs needed!

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/gouthamkulall615-art/pokemon-card-generator.git

# 2. Navigate into the project folder
cd pokemon-card-generator

# 3. Open index.html in your browser
open index.html
```

Or simply drag and drop `index.html` into your browser.

---

## 📁 Project Structure

```
pokemon-card-generator/
├── index.html       # Main HTML structure
├── style.css        # Styling and card design
├── script.js        # API calls and card logic
├── demo-img.jpg     # Demo screenshot
└── demo-img2.avif   # Demo screenshot (avif format)
```

---

## 🔌 API Reference

This project uses the **PokéAPI v2** — a free, open RESTful API for Pokémon data.

```
GET https://pokeapi.co/api/v2/pokemon/{name or id}
```

No API key required.

---

## 📸 How It Works

1. User enters a Pokémon name or ID in the search box
2. A `fetch()` request is sent to PokéAPI
3. The response data (name, stats, type, sprite) is extracted
4. A styled card is dynamically rendered in the DOM
5. Card colors adapt based on the Pokémon's type

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Goutham M**
- GitHub: [@gouthamkulall615-art](https://github.com/gouthamkulall615-art)

---

> Made with ❤️ and powered by [PokéAPI](https://pokeapi.co/)
