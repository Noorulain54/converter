# converter
pdf to word and jpg to pdf converter 
---

# PDF and JPG Converter

This project is a simple web application that allows users to convert PDF files to Word documents and JPG images to PDF files. Built with HTML, JavaScript, and CSS, it provides an easy-to-use interface for quick conversions without needing any backend setup.

## Features

- **PDF to Word Conversion**: Users can upload a PDF file and download its extracted content in a Word document format.
- **JPG to PDF Conversion**: Users can upload a JPG image and convert it into a PDF document.
- **Navigation Bar**: A simple navigation bar allows users to explore different pages, such as Home, About Us, How to Use, and Converter.

## Technologies Used

- **HTML**: For structuring the web pages.
- **CSS (Inline Styles)**: For basic styling of buttons, layout, and fonts.
- **JavaScript**: For handling file uploads, extracting text from PDFs, and creating PDF files.
- **Libraries**:
  - `pdf.js`: For reading PDF files and extracting text content.
  - `pdf-lib`: For generating PDF files from JPG images.
  - `FileSaver.js`: For downloading the converted files.

## Getting Started

### Prerequisites

No special software is required beyond a web browser, as this project is entirely client-side.

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/pdf-jpg-converter.git
   ```

2. **Navigate to the project folder**:

   ```bash
   cd pdf-jpg-converter
   ```

3. **Open `index.html` in a browser**:

   Double-click on `index.html` or open it in your preferred web browser.

## Usage

1. **Convert PDF to Word**:
   - Go to the **Converter** page.
   - Upload a PDF file by selecting it from your device.
   - Click **Convert to Word** to extract the text from the PDF and download it as a `.doc` file.

2. **Convert JPG to PDF**:
   - Go to the **Converter** page.
   - Upload a JPG image by selecting it from your device.
   - Click **Convert to PDF** to create a PDF document containing the image.

## Project Structure

```plaintext
pdf-jpg-converter/
├── index.html            # Home page
├── about.html            # About Us page
├── how-to-use.html       # How to Use page with instructions
├── converter.html        # Main conversion page
├── README.md             # Project documentation
└── assets/               # Folder for images, icons, etc. (if any)
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- [pdf.js](https://mozilla.github.io/pdf.js/) for PDF reading and extraction
- [pdf-lib](https://pdf-lib.js.org/) for PDF generation
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) for saving files on the client side

---
