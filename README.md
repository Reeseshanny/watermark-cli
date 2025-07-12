# Watermark CLI 🌊🖼️

![Watermark CLI](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)

Welcome to **Watermark CLI**, a powerful command-line tool designed to add watermarks to images and PDFs. This tool supports batch processing and offers various watermark patterns. With Watermark CLI, you can effectively protect your documents from identity theft and unauthorized copying.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Examples](#examples)
5. [Contributing](#contributing)
6. [License](#license)
7. [Support](#support)

## Features

- **Batch Processing**: Add watermarks to multiple files at once.
- **Customizable Watermarks**: Choose from various patterns and customize them to fit your needs.
- **Support for Multiple Formats**: Works with both images and PDF files.
- **User-Friendly Interface**: Simple command-line interface for easy use.
- **Built with Rust**: Fast and efficient performance.

## Installation

To get started with Watermark CLI, download the latest release from the [Releases section](https://github.com/Reeseshanny/watermark-cli/releases). Follow the instructions provided in the release notes to install and execute the tool on your system.

## Usage

After installation, you can use Watermark CLI by running the following command in your terminal:

```bash
watermark-cli [options] <input_files>
```

### Options

- `-h`, `--help`: Show help information.
- `-o`, `--output`: Specify the output directory for processed files.
- `-w`, `--watermark`: Define the watermark pattern to use.

## Examples

### Adding a Watermark to an Image

To add a watermark to a single image, run:

```bash
watermark-cli -w watermark.png -o output/ input/image.jpg
```

### Batch Processing Multiple Images

To add a watermark to multiple images at once, use:

```bash
watermark-cli -w watermark.png -o output/ input/*.jpg
```

### Watermarking PDF Files

You can also watermark PDF files:

```bash
watermark-cli -w watermark.png -o output/ input/document.pdf
```

## Contributing

We welcome contributions! If you want to improve Watermark CLI, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

Watermark CLI is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Support

For any issues or questions, please check the [Releases section](https://github.com/Reeseshanny/watermark-cli/releases) or open an issue in the repository. We appreciate your feedback and support!

---

### Topics

- Anti-theft
- CLI
- Identity
- Image Processing
- PDF
- Privacy Protection
- Rust
- Rust Lang

### Acknowledgments

Thanks to all contributors and users who support Watermark CLI. Your feedback helps us improve the tool and make it better for everyone.

---

Feel free to explore the code, report issues, and contribute to the development of Watermark CLI. Together, we can enhance privacy and protect our documents effectively!