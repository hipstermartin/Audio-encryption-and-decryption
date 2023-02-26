# Audio Encryption with RSA and AES Algorithms

This project implements an audio encryption and decryption system using RSA and AES algorithms. The system can be used to encrypt audio files and protect them from unauthorized access.

## Features

- Encrypts audio files using RSA and AES algorithms.
- Decrypts audio files using RSA and AES algorithms.
- Supports multiple audio file formats, such as MP3, WAV, FLAC, and more.

## Installation

Clone the repository:
  ```bash
  git clone https://github.com/your-username/audio-encryption.git
  ```
Install the required dependencies:
  ```bash
  pip install -r requirements.txt
  ```
## Usage

Generate RSA keys:
```bash
python generate_keys.py
```
Encrypt an audio file:
```bash
python encrypt.py -i input_file -o output_file -k public_key_file
```
Decrypt an audio file:
```bash
python decrypt.py -i input_file -o output_file -k private_key_file
```

## Contributing

Contributions are always welcome! If you have any suggestions or find any issues, please open an issue or a pull request.

## License

[MIT](https://choosealicense.com/licenses/mit/)
