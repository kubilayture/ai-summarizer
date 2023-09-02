# AI Summarizer

## Introduction

The AI Summarizer is a web application created using Vite, React, and Tailwind CSS. It allows users to input the URL of an article and receive concise summaries, making it easier to quickly grasp the main points of an article. This project also incorporates RTK Query for efficient data fetching and management.

## Features

- Input the URL of an article to summarize.
- Generate concise summaries of articles.
- View previously summarized URLs.
- Efficient data fetching and state management using RTK Query.
- User-friendly and responsive design.

## Installation

To get started with the AI Summarizer, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/kubilayture/ai-summarizer.git
   ```

2. **Navigate to the Project Directory**: Once the cloning process is complete, navigate to the project directory using the following command:

   ```bash
   cd ai-summarizer
   ```

3. **Install Dependencies**: To install the necessary dependencies for the app, run the following command:

   ```bash
   npm install
   ```

   Before proceeding to the next step, please make sure to create a RapidAPI key for the Article Extractor and Summarizer API on RapidAPI's website. Once you have the key, you'll need to save it as an environment variable in a `.env` file in the project root directory.

   ```plaintext
   VITE_RAPID_API_ARTICLE_KEY=your-rapidapi-key-here
   ```

4. **Run the App**: After successfully installing the dependencies, you can run the AI Summarizer locally using the following command:

   ```bash
   npm run dev
   ```

## How to Use

Using the AI Summarizer is straightforward. Follow these steps to summarize articles:

1. **Input an Article URL**: To summarize an article, paste the URL of the article you want to summarize into the input field on the app's main page.

2. **Summarize**: Once you've entered the article's URL, click the "Summarize" button. The app will initiate the summarization process, and within a moment, it will generate a concise summary of the article's main points.

3. **Saved Article URLs**: You can access and manage previously saved article URLs by clicking on the "Saved Article URLs" tab in the navigation bar. This section allows you to view the URLs of articles you have previously summarized, making it convenient to access and revisit the source articles.

With these simple steps, you can efficiently use the AI Summarizer to get quick and concise summaries of articles while keeping track of the source article URLs.

## Dependencies

The AI Summarizer relies on several key dependencies, each serving a specific purpose in the development and functionality of the application. Here are the main dependencies:

- **Vite**: Vite is a fast and lightweight build tool for JavaScript and React. It is the core of the development environment and aids in rapid development.

- **React**: React is a widely-used JavaScript library for building user interfaces. It forms the foundation of the application's component-based architecture.

- **Tailwind CSS**: Tailwind CSS is a utility-first CSS framework that streamlines styling and layout. It provides the app with a responsive and user-friendly design.

- **RTK Query**: RTK Query is a library for efficient data fetching and state management. It optimizes data retrieval and helps manage application state seamlessly.

You can find a complete list of the project's dependencies, including their versions, in the `package.json` file.
