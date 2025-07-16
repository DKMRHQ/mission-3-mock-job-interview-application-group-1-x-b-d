# AI Job Interview Simulator

---

This project is a web application designed to help users practice for job interviews. It simulates a technical interview experience by having an AI act as a hiring manager, asking questions based on a specified job title and dynamically responding to the user's answers.

## Features

* **AI-Powered Interviews**: Leverage the **Google Gemini 2.0 Flash API** to generate realistic interview questions and responses.
* **Customizable Job Titles**: Start an interview for any specific job role (e.g., "Frontend Developer", "Data Scientist", "Project Manager").
* **Interactive Chat Interface**: A user-friendly chat layout allows for a natural conversational flow.
* **Dynamic Questioning**: The AI adapts its questions based on your previous answers, mimicking a real interview.
* **Modern UI**: Built with **React.js** and **Material-UI (MUI)** for a clean, responsive, and engaging user experience.
* **Framer Motion Animations**: Subtle animations enhance the user interface's polish and fluidity.
* **Robust Error Handling**: Provides clear messages for API issues or network errors.

---

## Technologies Used

| Category      | Tools/Packages          |
| :------------ | :---------------------- |
| Frontend      | React.js                |
| UI Framework  | Material-UI (`@mui/material`) |
| Animations    | Framer Motion (`framer-motion`) |
| HTTP Client   | Axios                   |
| AI Model      | Google Gemini 2.0 Flash API |

---

## Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

* **Node.js**: Make sure you have Node.js (which includes npm) installed. You can download it from [nodejs.org](https://nodejs.org/).
* **Google Gemini API Key**: You'll need an API key for the Google Gemini API. Get one from the [Google AI Studio](https://aistudio.google.com/app/apikey).

### Installation

1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/DKMRHQ/mission-3-mock-job-interview-application-group-1-x-b-d.git](https://github.com/DKMRHQ/mission-3-mock-job-interview-application-group-1-x-b-d.git)
    cd mission-3-mock-job-interview-application-group-1-x-b-d
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Set up environment variables**:
    Create a `.env` file in the root of the project and add your Gemini API key:
    ```
    VITE_GEMINI_API_KEY=YOUR_GEMINI_API_KEY_HERE
    ```
    Replace `YOUR_GEMINI_API_KEY_HERE` with your actual API key.

### Run the Application

```bash
npm run dev
```
The application will typically start on http://localhost:5173 (or another available port). Open this URL in your web browser.

Usage
Enter Job Title: On the initial screen, type in the job title you want to practice for (e.g., "Software Engineer", "Marketing Specialist").

Start Interview: Click the "Start Interview" button. The AI hiring manager will then ask its first question.

Respond to Questions: Type your answers in the input field at the bottom and click "Send" or press Enter.

Continue the Conversation: The AI will ask follow-up questions based on your responses, simulating a dynamic interview experience.

Contributors
Brendon

DKMRHQ

Xevithirus

License
This project is for educational use and does not currently include a license file. Contributions and forks are welcome under fair use.
