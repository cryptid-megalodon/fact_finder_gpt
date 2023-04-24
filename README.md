FactFinderGPT
OpenAI Fact Highlighter Demo

OpenAI Fact Highlighter is a Chrome extension that uses OpenAI API to analyze text on a webpage and highlights sentences that are identified as factual assertions. This extension is perfect for quickly identifying key factual information on news articles, blog posts, and other text-heavy webpages.
Warning: This is a proof of concept for a larger project to detect facts and assign a credibility score based on corroborating websites. It is an experiment with the out-of-the-box fact classification capabilities of the GPT models and has many false positive / false negative classifications.

Features
* Highlights factual assertions in green
* Compatible with most webpages
* Easy-to-use popup button to initiate highlighting

Installation
1) Clone this repository to your local machine:
bash```git clone https://github.com/yourusername/openai-fact-highlighter.git```
2) Open Google Chrome, and navigate to chrome://extensions/.
3) Enable "Developer mode" in the top right corner of the page.
4) Click "Load unpacked" and select the openai-fact-highlighter directory.
The extension is now installed and ready to use. You will see the OpenAI Fact Highlighter icon in your browser's toolbar.

Dependencies
* See requirements.txt
* OpenAI API Key: This extension uses the OpenAI API and requires an API key to run. The first time you use the extension, you'll need to enter in your API key in the extension pop-up. The API key is stored locally in your browser for future use.

Usage
* Navigate to a webpage containing text that you'd like to analyze.
* Click the OpenAI Fact Highlighter icon in your browser's toolbar.
* Click the "Highlight Facts" button in the popup.

The extension will process the text on the page and highlight factual assertions in green.

Contributing
Contributions are welcome! Please feel free to submit a pull request or create an issue to report bugs or suggest new features.

License
This project is licensed under the MIT License. See the LICENSE file for details.
