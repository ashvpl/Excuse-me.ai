# Excuse-me.ai
Never get caught off guard again. Generate the perfect, plausible excuse for any situation, in just the right tone.
A web application that uses generative AI to create plausible excuses for any situation, complete with a visually compelling, AI-generated image.

## Live Demo

**You can view the live deployed application here:**

https://6000-firebase-studio-1746804224867.cluster-44kx2eiocbhe2tyk3zoyo3ryuo.cloudworkstations.dev/

---

## Features

- **AI-Powered Excuses:** Generate unique excuses based on category (Work, Social, Personal) and tone (Formal, Informal, Humorous).
- **Visual Context:** Generates a photorealistic image that visually represents the created excuse.
- **Copy to Clipboard:** Easily copy the generated excuse with a single click.
- **Responsive Design:** A clean and modern interface that works on all devices.

## Tech Stack

- **Framework:** [Next.js](https://nextjs.org/) (with App Router)
- **AI/ML:** [Google AI & Genkit](https://firebase.google.com/docs/genkit)
- **UI:** [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [ShadCN UI](https://ui.shadcn.com/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Deployment:** [Firebase Hosting](https://firebase.google.com/docs/hosting)

## How to Run Locally

To run this project on your own machine, follow these steps:

1.  **Download & Unzip:**
    Download and unzip the project folder.

2.  **Install dependencies:**
    Open a terminal in the project's root directory and run:
    ```bash
    npm install
    ```

3.  **Set up environment variables:**
    Create a file named `.env` in the root of the project and add your Google AI API key:
    ```
    GOOGLE_API_KEY=your_google_ai_api_key_here
    ```

4.  **Run the development server:**
    ```bash
    npm run dev
    ```

Open [http://localhost:9002](http://localhost:9002) with your browser to see the result.
