# DeepWiki Browser Extension

[![Greasy Fork](https://img.shields.io/greasyfork/dt/534333)](https://greasyfork.org/zh-CN/scripts/534333-deepwiki-button-enhanced)
[![Greasy Fork](https://img.shields.io/greasyfork/v/534333)](https://greasyfork.org/zh-CN/scripts/534333-deepwiki-button-enhanced)
[![License](https://img.shields.io/github/license/zhsama/deepwiki)](https://github.com/zhsama/deepwiki/blob/main/LICENSE)

A browser extension that adds a DeepWiki button to GitHub repository pages, providing easy access to documentation on DeepWiki.com.

## Features

- Adds a DeepWiki button to GitHub repository pages
- Integrates seamlessly with GitHub's UI as a list item in the repository details container
- Links directly to the corresponding DeepWiki page for the repository (deepwiki.com/{user}/{repo})
- Adapts to GitHub's UI changes and maintains consistent styling
- Works with GitHub's single-page application architecture

## Installation

### Option 1: Install from Greasy Fork (Recommended)

1. Install a UserScript manager extension for your browser:
   - [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Firefox, Safari, Edge)
   - [Greasemonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) (Firefox)
   - [Violentmonkey](https://violentmonkey.github.io/) (Chrome, Firefox, Edge)

2. Visit the DeepWiki Button Enhanced script page on Greasy Fork:
   - [DeepWiki Button Enhanced on Greasy Fork](https://greasyfork.org/zh-CN/scripts/534333-deepwiki-button-enhanced)

3. Click the green "Install" button on the Greasy Fork page

4. Confirm the installation when prompted by your UserScript manager

### Option 2: Install Directly from GitHub

1. Install a UserScript manager extension (see above)

2. Click on the following link to install the script:
   - [Install DeepWiki Button Enhanced from GitHub](https://github.com/zhsama/deepwiki/raw/main/deepwiki.js)

3. Confirm the installation when prompted by your UserScript manager

### As a Browser Extension (Coming Soon)

A packaged browser extension version will be available in the future.

## Screenshots

![DeepWiki Button on GitHub]()

*Note: Add actual screenshots of the DeepWiki button on GitHub to help users understand how it looks and where it appears.*

## How It Works

The extension:

1. Detects when you're browsing a GitHub repository page
2. Extracts the username and repository name from the URL
3. Creates a DeepWiki button that links to the corresponding DeepWiki page
4. Inserts the button as a list item in the repository details container
5. Maintains the button's presence during navigation within GitHub's single-page application

## Development

### Project Structure

- `deepwiki.js` - The main UserScript file that implements the DeepWiki button functionality

### Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue on the [GitHub repository](https://github.com/zhsama/deepwiki) or contact the maintainers.
