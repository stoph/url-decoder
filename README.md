# URL Parameter Decoder

A simple HTML tool to decode and analyze URL parameters in a clean table format.

## Usage

1. Open `index.html` in your browser
2. Paste a URL with parameters
3. Click "Decode URL" or press Enter
4. View decoded parameters in an organized table
5. Copy individual parameter values with the Copy button

## Features

- Decodes URL-encoded parameters
- Pretty-prints JSON data
- Copy individual values
- Clean, responsive design
- No dependencies - works offline

## Example

Input: `https://example.com/?name=John%20Doe&data=%7B%22id%22%3A123%7D`

Output:
- `name`: John Doe
- `data`: `{"id": 123}`
