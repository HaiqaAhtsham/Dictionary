# Smart Text Editor
## 1. Introduction
The Smart Text Editor is a C++ project that functions as an intelligent text editor, offering features such as smart word completion, text compression, saving, and loading text files. It is designed to enhance information consistency and provide an adaptable platform for text editing.

## 2. Project Purpose
The primary goal of this project is to develop a user-friendly text editor in C++ that caters to a wide range of users. The editor is based on the C++ platform, allowing for easy customization by programmers and ensuring adaptability to various needs.

## 3. Project Features
###  Word Completion Suggestions
User is presented with words completion options.
### Typing Text:
Users can type text on the console, and the editor supports forward typing without backward editing.
### Word Completion Suggestions:
The editor provides word completion suggestions based on a fixed dictionary using trie trees or B-trees.

### Compression of Text:
Utilizes Huffman encoding to compress text, reducing its length while maintaining all original information.
Provides added utilities like compression and security.

### Saving and Loading:
Enables users to save the compressed text and compression tree to a file on their local machine.
Allows loading of compressed text and compression tree for further editing.
### Security:
At times, the information is confidential and its security is an utmost priority. If
the medium to store the data or communicate isn’t reliable enough, we need to
still ensure security. In such scenarios, text is stored or transferred in a form
that is only understood by the intended recipient. For others, it is just gibberish.
This falls under the domain of cyber-security(specifically cryptography) and has
many applications.

### Uncompressing of Text:
Recovers the original text by loading the Huffman compression tree and decompressing the compressed text.
### Continue Editing:
Users can resume typing from where they left off, save their progress, and reload files multiple times.

## 4. Implementation Guidelines
Detailed guidelines for implementing major functionalities, including typing text, word completion suggestions, compression, saving/loading, uncompressing, and continuing editing, are provided in the project documentation. Use vector strings, iterators, loops, trie trees, B-trees, and Huffman encoding as instructed.

## Contributing
Feel free to contribute to the project by submitting bug reports, feature requests, or pull requests. Please adhere to the established coding conventions and functional programming principles.

