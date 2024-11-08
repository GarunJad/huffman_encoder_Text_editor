# Huffman Encoding Text Editor

A text editor application implemented in C++ that includes Huffman encoding functionality. This project demonstrates file handling, efficient text compression using Huffman encoding, and data structures such as stacks, linked lists, and minheaps to manipulate and store the encoded data. The editor allows users to write, edit, and save text files, as well as compress and decompress the text using the Huffman encoding algorithm.

## Features

- **Text Editor**: Basic text editing functionalities such as writing, editing, and saving text files.
- **Huffman Encoding**: Efficient text compression using Huffman encoding to reduce file sizes.
- **File Handling**: Load and save text files with options to compress and decompress the content.
- **Data Structures Used**:
  - **Stack**: For undo/redo operations or temporary storage.
  - **Linked List**: Used for text management and editing.
  - **MinHeap**: Key component in Huffman encoding for building the Huffman tree.
- **Compression and Decompression**: Encode text into a compressed format and decode it back to the original text.

## Data Structures & Algorithms

- **Huffman Encoding**: A lossless data compression algorithm that assigns variable-length codes to characters based on their frequencies. Characters with higher frequencies get shorter codes, thereby reducing the overall size of the file.
- **MinHeap**: This is used to create the priority queue required for building the Huffman Tree. The nodes with the smallest frequencies are extracted first.
- **Linked List**: Used for managing text data, allowing for efficient insertion, deletion, and traversal.
- **Stack**: A stack is utilized for managing undo and redo operations in the text editor.

## Getting Started

### Prerequisites

To run this project, you need:

- C++11 or higher
- A C++ compiler (e.g., g++, clang++)
- Basic knowledge of data structures like stacks, linked lists, and heaps

### Compilation

Use the following command to compile the code  on Linux:

```bash
g++ -std=c++11 -o text_editor huffman_text_editor.cpp
