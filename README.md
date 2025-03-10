# WSP ChatBot

A simple and free chatbot powered by DeepSeek-R1, built using HTML, JavaScript, and Bootstrap.

## Features
- User-friendly interface with Bootstrap styling
- Communicates with OpenRouter API to generate responses
- Displays chatbot responses in markdown format using `marked.js`

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/mrshahbaznnsd/chatbot.git
   ```
2. Navigate to the project folder:
   ```sh
   cd wsp-chatbot
   ```
3. Open `chat.html` in your web browser.

## Usage
1. Enter a message in the input field.
2. Click the "Ask!" button.
3. The chatbot will respond based on the DeepSeek-R1 model.

## Requirements
- Internet connection
- Web browser with JavaScript enabled

## API Configuration
This project uses OpenRouter AI API. Ensure you update the `Authorization` token in the `sendMessage()` function before deployment:
```js
Authorization: 'Bearer YOUR_API_KEY_HERE'
```

## Technologies Used
- HTML
- Bootstrap (CDN)
- JavaScript (Fetch API)
- OpenRouter API
- Marked.js (for Markdown rendering)

## Disclaimer
**Do not expose your API key in public repositories.** Use environment variables or backend proxying for security.

## License
This project is open-source and available under the MIT License.

## Contribution
Feel free to fork this repository, submit issues, or create pull requests to enhance the chatbot.

---

### Contact
For any inquiries, reach out via email at **mrshahbaznns@gmail.com** or WhatsApp at **+923061081842**.

