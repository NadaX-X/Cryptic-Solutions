## Encryption-Decryption-System

The application is designed to encrypt and decrypt messages provided by the user, 
along with the necessary key, in order to ensure data integrity and confidentiality.

The program was developed using the C# programming language.


## Features
Allows users to encrypt and decrypt a text data.


## Encryption Block Diagram
The plaintext is split into two equal halves
Then each half will be shifted left by two .
Then combine the two Parts .
Then XORed them with encryption Key that is inserted by the user to obtain the ciphertext.

## Decryption Block Diagram
The ciphertext is XORed with the encryption key .
Then the decrypted plaintext is split into two equal halves.
Each half of the decrypted plaintext is shifted right by two.
Then the shifted halves are combined to obtain the original plaintext.

## Key Block Diagram
The Key will be shifted left by two.
Then passes through P-Box transformation to genertate the new key.

## Usage
1. Clone the repository to your local machine.
2. Open the project in Visual Studio.
3. Run the Program.cs file to start the application.
4. When prompted, enter your name (or type 'stop' to exit the program).
5. Enter your desired key.
6. The application will display the encrypted ciphertext and the decrypted plaintext.

## Contribution

If you find any issues or have suggestions for improvements, please feel free to create a new issue or submit a pull request. Contributions are welcome!

## License

This project is licensed under the [MIT License](LICENSE).
