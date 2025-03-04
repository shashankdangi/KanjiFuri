# KanjiFuri - A Simple Rich Text Editor with Furigana Support ✨🖋️

KanjiFuri is a web-based rich text editor that allows users to add Furigana (pronunciation guides for kanji characters) to selected text and download the edited content as a PDF. It supports basic text formatting like bold, italic, and underline, and integrates a simple toolbar for easy editing. 📝

## Features 🌟
- **Rich Text Formatting**: Apply bold, italic, and underline styles to text. **(B, I, U)** ✨
- **Furigana Support**: Add Furigana (pronunciation guides) to selected kanji text. 🈴🉐
- **Download as PDF**: Convert and download the edited content as a PDF while preserving text formatting. 📄🔽
- **Keyboard Shortcuts**: Use `Ctrl+F` to quickly add Furigana to selected text. ⌨️

## Technologies Used 🔧
- **HTML5**: Markup for structuring the editor. 🖥️
- **CSS**: Basic styling (can be extended with your custom styles). 🎨
- **JavaScript**: For functionality such as text formatting, adding Furigana, and generating PDFs. 💻
- **html2pdf.js**: To convert the content into a downloadable PDF. 📥
- **DOMPurify**: For sanitizing the content, ensuring safety and security. 🛡️
- **jsPDF**: For generating the PDF with enhanced rendering precision for Japanese characters. 📚

## How to Use 🛠️

1. Open the editor in your browser. 🌐
2. Start typing or paste your content inside the editor. 🖋️
3. Use the **B**, **I**, and **U** buttons for basic text formatting (bold, italic, and underline). 🅱️🅸🆎
4. Highlight the kanji text you want to add Furigana to and click the **Add Furigana** button or press `Ctrl+F` to input the Furigana pronunciation. 📖🔤
5. Once your content is ready, click the **Download PDF** button to download your content as a PDF file. 📥

## Demo 🎬

You can see the demo [here](https://shashankdangi.github.io/KanjiFuri). 🌍

## Installation 🔽

To run the project locally, clone this repository and open the `index.html` file in your browser.

```bash
git clone https://github.com/your-username/kanjifuri.git
cd kanjifuri
open index.html
