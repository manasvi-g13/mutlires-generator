# MultiRes – AI Resume Generator & Job Matcher

## Overview

MultiRes is an AI-powered platform that helps job seekers tailor their resumes to specific job descriptions and improve their chances of passing recruiter and ATS screening processes.

The platform analyzes a user's resume, compares it against a target job description, identifies skill gaps, and generates optimized resume content aligned with the role requirements.

## Problem

Job seekers often apply to dozens of positions using the same resume, resulting in poor alignment with job requirements and lower ATS visibility.

MultiRes addresses this challenge by automatically analyzing both resumes and job descriptions, providing intelligent recommendations and resume enhancements.

## Features

- Resume parsing and analysis
- Job description matching
- ATS compatibility assessment
- Skill gap identification
- AI-powered resume optimization
- Resume generation and enhancement
- Match score calculation
- Personalized improvement recommendations

## Tech Stack

### Frontend
- React
- TypeScript

### Backend
- Node.js
- Express

### AI & NLP
- OpenAI API
- Hugging Face Models
- Natural Language Processing

### Database
- PostgreSQL

## Workflow

1. Upload resume
2. Input target job description
3. Extract and analyze resume content
4. Compare skills and experience against job requirements
5. Generate match score and recommendations
6. Produce an optimized resume version

## Business Impact

MultiRes helps users:

- Improve ATS compatibility
- Identify missing skills and keywords
- Tailor resumes for specific roles
- Reduce manual resume customization effort
- Increase application quality

## Installation

### Clone Repository

```bash
git clone https://github.com/manasvi-g13/mutlires-generator.git
cd mutlires-generator
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create a `.env` file and configure:

```env
OPENAI_API_KEY=
HF_TOKEN=
JOB_TABLE=
PGHOST=
PGDATABASE=
PGUSER=
PGPASSWORD=
```

### Run Application

```bash
npm run dev
```

## Author

Manasvi Gandhi
