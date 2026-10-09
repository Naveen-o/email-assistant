# 📧 Smart Email Assistant

## 1. Short Description

Smart Email Assistant is an AI-powered application that generates context-aware email replies using Google Gemini. Built with Spring Boot and React, it allows users to generate replies based on email content and selected tones. A Chrome extension integrates the functionality directly into Gmail, making email communication faster and more convenient.

## 2. Tools and Technologies

- **Language:** Java, JavaScript
- **Backend:** Spring Boot, Spring AI
- **Frontend:** React.js
- **AI Integration:** Google Gemini API
- **Browser Integration:** Chrome Extension
- **API Communication:** REST API
- **Build Tool:** Maven
- **Development Tools:** IntelliJ IDEA, VS Code, Postman

## 3. Features

- **AI-Powered Reply Generation:** Generates relevant email replies using Google Gemini.
- **Custom Reply Tones:** Supports different tones, such as professional, friendly, and casual.
- **Gmail Integration:** Provides AI-assisted reply generation directly within Gmail through a Chrome extension.
- **REST API Integration:** Connects the React frontend with the Spring Boot backend.
- **Improved Productivity:** Reduces the time and effort required to compose email responses.

## 4. Process

1. **Enter Email Content:** Provide the email content for which a reply is required.
2. **Select Reply Tone:** Choose the preferred tone for the generated response.
3. **Send API Request:** The React frontend sends the email content and selected tone to the Spring Boot backend.
4. **Generate AI Reply:** Spring AI integrates with the Google Gemini API to generate a context-aware response.
5. **Display the Response:** The generated reply is returned to the frontend for review.
6. **Use in Gmail:** The Chrome extension brings AI reply generation into the Gmail interface for a more convenient workflow.

## 5. How to Run the Project

### Prerequisites

- Java Development Kit (JDK)
- Node.js and npm
- Maven
- Google Gemini API key
- Google Chrome

### Step 1: Clone the Repository

```bash
git clone https://github.com/Naveen-o/email-assistant.git
cd <project-folder>
```

### Step 2: Configure the Backend

1. Open the Spring Boot backend in your IDE.
2. Configure your Google Gemini API key using the configuration expected by your application.
3. Verify the required dependencies in `pom.xml`.
4. Run the Spring Boot application.

Alternatively, if the Maven wrapper is available:

```bash
./mvnw spring-boot:run
```

On Windows:

```bash
mvnw.cmd spring-boot:run
```

### Step 3: Run the React Frontend

Navigate to the frontend directory:

```bash
cd <frontend-folder>
npm install
```

Start the application using the script defined in `package.json`, for example:

```bash
npm start
```

If the project uses Vite, use `npm run dev` instead.

### Step 4: Load the Chrome Extension

1. Open Google Chrome.
2. Navigate to `chrome://extensions/`.
3. Enable **Developer mode**.
4. Click **Load unpacked**.
5. Select the Chrome extension's directory.
6. Open Gmail and test the AI reply functionality.

### Step 5: Test the Application

Ensure the backend and frontend are running, verify the API connection, and test reply generation with different email content and tones.

**Note:** Replace the placeholder paths and commands with the actual repository structure and scripts. Keep API keys private and never commit them to GitHub.
