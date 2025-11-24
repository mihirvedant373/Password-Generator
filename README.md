# Python Secure Text Encryptor

A simple but secure command-line tool to encrypt and decrypt text messages using a custom passkey.

##  Features

- **AES Encryption:** Uses the Fernet (Symmetric Encryption) standard for high security.
- **SHA-256 Key Derivation:** Converts any user password into a valid 32-byte encryption key using SHA-256 hashing.
- **Base64 Encoding:** Ensures encrypted output is safe for text storage or transmission.
- **User-Friendly CLI:** Simple menu-driven interface (Select 1 for Encrypt, 2 for Decrypt).

##  Technologies Used

- Python 3.x
- `cryptography` library
- `hashlib` (Built-in)
- `base64` (Built-in)

##  Installation


       HOW TO INSTALL AND RUN THE SECURE ENCRYPTION TOOL
                 (Linux / Kali Linux Guide)


STEP 1: INSTALL REQUIREMENTS
------------------------------------------------------------
Before running the tool, you need to install the cryptography
library. Open your terminal and type:

    pip install cryptography


STEP 2: CREATE THE FILE
------------------------------------------------------------
Create the Python file using the nano editor (it is easier 
to paste code here than using cat).

1. Open the file:
    nano Your_file_name.py

2. Paste the Python code into the .py file.

3. Save and Exit:
   - Press 'Ctrl + X'
   - Press 'Y'
   - Press 'Enter'


STEP 3: SET PERMISSIONS
------------------------------------------------------------
You need to give the file permission to execute. Run:

    chmod +x Your_file_name.py


STEP 4: RUN THE TOOL
------------------------------------------------------------
Now you can run the program:

    python3 Your_file_name.py

##  Code Link ##
https://github.com/mihirvedant373/Password-Generator/commit/761c4e5be37ea9ce00863a658f3ec476e2acad84


                 TROUBLESHOOTING

* If 'pip' is not found, try using:  apt install python3-pip
* If you get an indentation error, make sure the code was
  pasted correctly without extra spaces.
