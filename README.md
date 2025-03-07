# Smart Email Assistant

🚀 AI-powered email reply assistant built with **Spring Boot, Spring AI, Google API, React, and a Chrome Extension**.

## Features
- ✉️ **AI Reply Button**: Generates intelligent email replies with a single click.
- 🤖 **Spring AI Integration**: Leverages AI to draft context-aware responses.
- 🌐 **Google API**: Seamless integration with Gmail for fetching and replying to emails.
- 🎨 **React Frontend**: A user-friendly interface for managing AI-generated responses.
- 🧩 **Chrome Extension**: Enhances Gmail by adding an "AI Reply" button.

## Tech Stack
- **Backend**: Spring Boot, Spring AI, Google API
- **Frontend**: React, JavaScript
- **Browser Extension**: JavaScript

## Setup Instructions

### Backend Setup (Spring Boot)
1. Clone the repository:
   ```bash
   git clone https://github.com/aryantiwari522/Smart-email-assistant.git
   cd Smart-email-assistant
   ```

2. Configure **Google API credentials** for Gmail access.
3. Build and run the backend:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

### Frontend Setup (React)
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies and start the frontend:
   ```bash
   npm install
   npm start
   ```

### Chrome Extension Setup
1. Open **Chrome** and go to `chrome://extensions/`.
2. Enable **Developer Mode**.
3. Click **Load Unpacked** and select the `extension` folder.
4. Open Gmail and see the **AI Reply** button in action!

## How It Works
1. Open Gmail.
2. Click on an email.
3. Press the **AI Reply** button.
4. AI generates a response, which you can edit or send instantly!

## Future Enhancements
- ✅ Customizable AI response styles
- ✅ Support for multiple email accounts
- ✅ Voice-to-text AI replies

## Contributing
Pull requests are welcome! Feel free to open issues and suggest improvements.

## License
📜 MIT License
