# CPSP Syntax Highlighting for VSCode

This is a personal project that adds syntax highlighting support for CPSP (C++ Server Pages) files in Visual Studio Code. **CPSP** is a format used by the [Poco C++ Libraries](https://pocoproject.org/) to embed C++ code within HTML, similar to PHP. This extension enables VSCode users to work more effectively with CPSP files by providing basic syntax highlighting for both C++ and HTML within the same document.

## Features

- **C++ Syntax Highlighting**: Embedded C++ code within `<% ... %>` tags is highlighted, making it easier to read and maintain.
- **HTML Syntax Highlighting**: Recognizes standard HTML tags and attributes, applying HTML highlighting to non-C++ content.
- **CSS Support within `<style>` Tags**: Supports CSS syntax within `<style>` tags, offering a complete editing experience.

## Why This Project Exists

This extension was created as a personal project to improve the development experience with CPSP files. Since I can't find existing VSCode extension to support the CPSP format specifically, this project fills the gap by providing syntax highlighting for both C++ and HTML in CPSP documents. It's designed to make it easier to work with mixed C++ and HTML content, as often found in server-side projects using Poco C++ Libraries.

## Installation

1. Clone or download this repository.
2. In the root directory, run:
   ```bash
   npx vsce package
   ```
   This will generate a `.vsix` file.
3. Open Visual Studio Code, go to the **Extensions** sidebar, click on the `...` menu, and select **Install from VSIX...**.
4. Select the `.vsix` file generated in the previous step to install the extension locally.

## Usage

Once installed, open any `.cpsp` file in VSCode to see the syntax highlighting in action. C++ code inside `<% ... %>` tags will be highlighted according to C++ syntax, while HTML elements will follow standard HTML highlighting.

## Limitations

This extension is designed for basic syntax highlighting and may not cover all edge cases within the CPSP format. Future updates may include support for additional Poco-specific syntax or other improvements to the HTML/C++ highlighting.

## Contributing

Since this is a personal project, contributions are not actively solicited. However, if you have suggestions or improvements, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
