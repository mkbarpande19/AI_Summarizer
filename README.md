
# Open AI Summarizer App

ChatGPT AI SaaS Business with React.


## About

 - Setup a ReactJS project using Vite
 - Responsive UI/UX
 - Conditional API Requests
 - Storing History data using localStorafe
 - Handling the onclick and submit functionality
 - Implemented copy to clipboard functionality
 
## Installation

Install open AI summarizer app with npm

```bash
  cd AI_Summarizer
  npm install 
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`VITE_RAPID_API_ARTICLE_KEY`

After Adding the variable to .env file run the project with following command
```bash
  npm run dev 
```
    
## API Reference

#### Get all items

```http
  GET https://article-extractor-and-summarizer.p.rapidapi.com/summarize
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |
