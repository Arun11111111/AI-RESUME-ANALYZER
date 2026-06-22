# AI Resume Analyzer

## Overview

AI Resume Analyzer is a MERN Stack application that uses Artificial Intelligence to analyze PDF resumes and provide detailed feedback. The system evaluates ATS compatibility, extracts skills, identifies strengths and weaknesses, and offers personalized suggestions to help users improve their resumes and increase their chances of securing job interviews.

## Features

* PDF resume upload and analysis
* AI-powered resume evaluation
* ATS score calculation
* Skill extraction and analysis
* Resume content assessment
* Personalized improvement suggestions
* Secure user authentication (JWT)
* Resume history management
* Responsive and user-friendly interface

## Tech Stack

**Frontend:** React.js, Axios, Tailwind CSS

**Backend:** Node.js, Express.js

**Database:** MongoDB, Mongoose

**AI Integration:** Gemini API / OpenAI API

**File Processing:** PDF Parser, Multer

## How It Works

1. Upload a PDF resume.
2. The system extracts resume content.
3. AI analyzes skills, experience, and formatting.
4. An ATS score is generated.
5. Users receive detailed feedback and improvement recommendations.

## Installation

```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
npm install
```

Create a `.env` file:

```env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
AI_API_KEY=your_api_key
PORT=5000
```

Run the project:

```bash
npm run dev
```

## Future Enhancements

* Job description matching
* Resume builder
* Cover letter generation
* Advanced ATS optimization

## License

MIT License
