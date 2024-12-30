
# C-Harvester

**C-Harvester** is a tool developed to scan web pages for credit card information, validate card numbers using the Luhn algorithm, and identify card types based on a BIN (Bank Identification Number) database. This tool is intended for ethical, responsible use only.

---

## Features

- **Credit Card Detection**: Scans web pages for card number patterns (13-19 digits).
- **Card Validation**: Verifies the authenticity of the detected card numbers using the Luhn algorithm.
- **BIN Lookup**: Identifies the card type (Visa, MasterCard, etc.) using a comprehensive BIN database.
- **Progress Monitoring**: Real-time progress updates while scanning the provided URL.
- **Detailed Output**: Displays detected card details, including the card type, BIN, and full card number (cleaned of spaces/dashes).

---

## Ethical Disclaimer

**C-Harvester** is designed to be used **only for ethical and authorized purposes**. Unauthorized collection or use of sensitive data is illegal and violates privacy regulations. You must have explicit permission to scan any web URL.

By using this tool, you agree to use it in compliance with legal and ethical standards.

---

## Installation

Follow these steps to install and use **C-Harvester**:

### 1. Clone the Repository

```bash
git clone https://github.com/cypherdavy/C-Harvester.git
```

### 2. Install Dependencies

Ensure you have the necessary dependencies installed:

```bash
pip install -r requirements.txt
```

### 3. Running the Script

After installation, run the tool:

```bash
python c-harvestor.py
```

---

## Usage

1. **Agree to the Disclaimer**: Before proceeding, you must accept the ethical use disclaimer.
2. **Enter a URL**: Provide the URL of the page you wish to scan for credit card information.
3. **View Results**: The tool will display any detected credit card information, including:
   - Card Type (e.g., Visa, MasterCard, etc.)
   - BIN (Bank Identification Number)
   - Full Card Number (masked for security)

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## Author

**DavyCipher**  
[GitHub Profile](https://github.com/cypherdavy)

---

## Contact

For questions, issues, or contributions, feel free to open an issue or contact the project author via GitHub.

---

> **Important**: Always ensure you have explicit permission before scanning any website. Ethical hacking and responsible usage of such tools are vital to maintaining security and privacy standards.
