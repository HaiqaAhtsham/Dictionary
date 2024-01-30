# Smart Text Editor
## 1. Introduction
The Smart Text Editor is a C++ project that functions as an intelligent text editor, offering features such as smart word completion, text compression, saving, and loading text files. It is designed to enhance information consistency and provide an adaptable platform for text editing.

## 2. Project Purpose
The primary goal of this project is to develop a user-friendly text editor in C++ that caters to a wide range of users. The editor is based on the C++ platform, allowing for easy customization by programmers and ensuring adaptability to various needs.

## 3. Project Features
### User Flow
### Typing Text:
Users can type text on the console, and the editor supports forward typing without backward editing.
Word Completion Suggestions:
The editor provides word completion suggestions based on a fixed dictionary using trie trees or B-trees.

### Compression of Text:
Utilizes Huffman encoding to compress text, reducing its length while maintaining all original information.
Provides added utilities like compression and security.

### Saving and Loading:
Enables users to save the compressed text and compression tree to a file on their local machine.
Allows loading of compressed text and compression tree for further editing.

### Uncompressing of Text:

Recovers the original text by loading the Huffman compression tree and decompressing the compressed text.
### Continue Editing:
Users can resume typing from where they left off, save their progress, and reload files multiple times.
## 4. Implementation Guidelines
Detailed guidelines for implementing major functionalities, including typing text, word completion suggestions, compression, saving/loading, uncompressing, and continuing editing, are provided in the project documentation. Use vector strings, iterators, loops, trie trees, B-trees, and Huffman encoding as instructed.
