# Pyfuscator

## Overview

- **Pyfuscator** is a Python tool designed to obfuscate Python scripts by encoding and encrypting them. It allows you to transform your Python code into an obfuscated form, which can help in hiding the logic of the script and potentially evade basic static analysis.

## Features

- **Python Code Obfuscation:** Converts Python code into a base64-encoded and XOR-encrypted format to make it harder to understand.
- **Simple CLI Interface:** Provides an easy-to-use command-line interface for inputting code and generating obfuscated output.
- **Customizable Output:** Allows specifying the output file name for the obfuscated code.
- **Base64 Encoding & XOR Encryption:** Utilizes base64 encoding combined with XOR encryption for added obfuscation.

## How to Use
![Pyfuscator](https://github.com/user-attachments/assets/df9b9c1c-95c5-4fea-b85a-8e1dc475df92)

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/malwarekid/Pyfuscator.git && cd Pyfuscator
    ```

2. **Run the Script:**

    ```bash
    python3 Pyfuscator.py
    ```

```
    ____        ____                      __            
   / __ \__  __/ __/_  ________________ _/ /_____  _____
  / /_/ / / / / /_/ / / / ___/ ___/ __ `/ __/ __ \/ ___/
 / ____/ /_/ / __/ /_/ (__  ) /__/ /_/ / /_/ /_/ / /    
/_/    \__, /_/  \__,_/____/\___/\__,_/\__/\____/_/     
      /____/                                            
                                        By @malwarekid  

Welcome to Pyfuscator!
Enter your python code to obfuscate (leave empty for program path): 
Enter your python program path: hello.py
Enter your obfuscated program name (default obfuscate.py): hello-obf.py
Obfuscated program has been saved as hello-obf.py 
```

3. **Enter Input Parameters:**

   - **Python Code:** Enter the Python code you wish to obfuscate directly or provide the path to a Python script file.
   - **Obfuscated Program Name:** Specify the name of the output file for the obfuscated code (default is `obfuscate.py`).

4. **Output File:** The obfuscated Python code will be saved in the specified output file.

## Requirements

- Python 3.x
- `colorama` module

## Installation

Ensure you have the required dependencies:

```bash
pip3 install colorama
```

## Example

Run the script:

```bash
python3 Pyfuscator.py
```

When prompted:

```
Enter your python code to obfuscate (leave empty for program path):
Enter your python program path:
Enter your obfuscated program name (default obfuscate.py):
```

The script will generate an obfuscated Python file with the name you specified.

## Contributors

- [MalwareKid](https://github.com/malwarekid)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Notes

Feel free to contribute, report issues, or provide feedback. Don't forget to follow me on [Instagram](https://www.instagram.com/malwarekid/) and [GitHub](https://github.com/malwarekid/). Happy Obfuscating!
