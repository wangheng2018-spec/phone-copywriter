# Phone Copywriter

AI-powered sales script generator for second-hand mobile phone listings. Input product details and instantly get professional, persuasive marketing copy.

## Features

- **Smart Copy Generation** – Automatically creates compelling sales scripts based on phone specifications
- **Multiple Script Styles** – Supports various tones: professional, casual, enthusiastic, and more
- **Real-time Preview** – See generated copy instantly with a clean, mobile-friendly interface
- **Customizable Inputs** – Tailor copy by model, condition, price, and key selling points
- **Bilingual Support** – Generates copy in both Chinese and English
- **Copy to Clipboard** – One-click copy for easy use in listings or messages

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Custom CSS with responsive grid layout
- **Fonts**: System fonts optimized for Chinese and English (Microsoft YaHei, PingFang SC)
- **No external dependencies** – Lightweight, fast, and easy to deploy

## Project Structure

```
phone-copywriter/
├── index.html          # Main application page
├── css/
│   └── style.css       # Styles and responsive design
├── js/
│   ├── app.js          # Core logic and state management
│   ├── generator.js    # Copy generation algorithms
│   └── templates.js    # Script templates and variations
└── assets/
    └── icons/          # UI icons and graphics
```

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/phone-copywriter.git
   cd phone-copywriter
   ```

2. **Open the application**
   - Simply open `index.html` in any modern web browser
   - Or serve it locally:
     ```bash
     python -m http.server 8000
     ```
   - Navigate to `http://localhost:8000`

3. **Generate copy**
   - Fill in phone details (brand, model, condition, price)
   - Select desired script style
   - Click "Generate" to create your copy
   - Use the copy button to save it to your clipboard

## Usage Tips

- **Be specific** – Include exact model numbers, storage capacity, and condition details for better results
- **Highlight unique selling points** – Mention accessories, warranty, or special features
- **Adjust tone** – Choose different styles for different platforms (e.g., professional for eBay, casual for Facebook Marketplace)
- **Review and edit** – Generated copy serves as a strong starting point; customize to match your voice

## License

MIT License – feel free to use, modify, and distribute.