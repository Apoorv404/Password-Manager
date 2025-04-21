# Password-Manager

A secure offline password manager built with Python and Tkinter that helps you generate, store, and manage your passwords locally.

## Features

- **Password Generation**: Automatically generates strong passwords with a mix of letters, numbers, and symbols
- **Secure Storage**: Stores all passwords locally in a JSON file
- **Search Functionality**: Quickly find stored passwords for any website
- **Clipboard Integration**: Automatically copies generated passwords to clipboard
- **User-Friendly Interface**: Simple and intuitive graphical interface

## How to Use

1. **Add New Password**:
   - Enter the website name
   - Enter your email/username
   - Either enter your password or click "Generate Password"
   - Click "Add" to save

2. **Find Existing Password**:
   - Enter the website name
   - Click "Search" to retrieve stored credentials

3. **Generate Strong Password**:
   - Click "Generate Password" to create a secure password
   - The generated password is automatically copied to your clipboard

## Requirements

- Python 3.x
- Tkinter (usually comes with Python)
- pyperclip

## Security Note

All passwords are stored locally on your machine in a JSON file. No data is transmitted over the internet, making it secure from online threats.

## File Structure

- `main.py`: Main application file
- `logo.png`: Application logo
- `data.json`: Password storage file (created automatically)
