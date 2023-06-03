
# Open AI Summarizer App

ChatGPT AI SaaS Business with React.

#### Data Loading
![screencapture-localhost-5173-2023-06-03-14_41_22](https://github.com/mkbarpande19/AI_Summarizer/assets/56429231/62ec1644-43e6-4aef-a742-cf065f416f4d)

#### Data Loaded Successfully
![screencapture-localhost-5173-2023-06-03-14_41_44](https://github.com/mkbarpande19/AI_Summarizer/assets/56429231/1c65ad33-4779-4af1-b1ef-741ee7467a4a)



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


## Tech Stack

**Technologies:** React, Redux-Toolkit, TailwindCSS

**API Server:** RapidApi

