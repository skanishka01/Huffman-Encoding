# Huffman Encoding

## Overview
Huffman Encoding is a data compression algorithm that reduces the size of data by assigning shorter codes to frequently occurring characters. This project implements Huffman Encoding using a priority queue and a binary tree to build variable-length prefix codes for each character in the input string.

---

## Features
- **Count the frequency** of characters in the input string.
- **Build a Huffman tree** based on character frequencies.
- **Generate a lookup table** for characters and their corresponding Huffman codes.
- **Encode a given string** using Huffman codes.
- **Decode a bit sequence** back to the original string using the Huffman tree.

---

## Getting Started

### Prerequisites
To run this project, ensure that you have a **C++ compiler** installed on your machine.

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/huffman-encoding.git
   ```
2. **Compile the source code:**
   ```bash
   g++ huffman_encoding.cpp -o huffman_encoding
   ```

---

## Usage
1. **Run the executable:**
   ```bash
   ./huffman_encoding
   ```
2. **Enter the string** you want to encode when prompted.
3. The program will display:
   - **Huffman codes** for each character in the input string.
   - **Encoded string** representation.
   - **Decoded string**, verifying the correctness of the encoding.

---

## Example
![Huffman Encoding Example](https://github.com/user-attachments/assets/a424b05f-9bdf-4243-865d-7eb1c5eb2f6e)

---

## Contributing
Contributions are welcome! If you find any issues or want to add new features:
- **Fork the repository**
- **Create a new branch**
- **Commit your changes**
- **Open a pull request**

Feel free to modify this README with additional details as needed!

---

