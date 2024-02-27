# QR Code Generator Project

This project is a simple QR code generator implemented in Node.js. It prompts the user to input a URL, generates a QR code image in PNG format, and saves it to a file named `qr_img.png`. Additionally, it saves the entered URL to a text file named `URL.txt`.

## Requirements
- Node.js installed on your machine

## Usage
1. Clone the repository to your local machine.
2. Navigate to the project directory in the terminal.
3. Run the following command to install the required dependencies:
   ```
   npm install
   ```
4. Execute the script using the following command:
   ```
   node index.js
   ```
5. You will be prompted to type in a URL.
6. After entering the URL, a QR code image will be generated and saved as `qr_img.png`. The entered URL will also be saved in a text file named `URL.txt`.

## Example
```
PS C:\path\to\project> node index.js
? Type in your URL: https://www.example.com
The file has been saved!
```

## Dependencies
- [inquirer](https://www.npmjs.com/package/inquirer): For interactive command-line user interfaces.
- [qr-image](https://www.npmjs.com/package/qr-image): For generating QR code images.
- [fs](https://nodejs.org/api/fs.html): Node.js file system module.

## Troubleshooting
- If you encounter any issues during the execution, ensure that Node.js is installed on your machine.
- If the prompt cannot be rendered, check your terminal environment.

Feel free to customize and extend this project based on your needs. Happy coding!