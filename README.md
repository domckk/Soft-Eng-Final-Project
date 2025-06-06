# Vital Link: AI-Driven Healthcare Chatbot

## Project Overview
 An AI chatbot that can diagnos your disease based on the provided symptoms that has been given.

## Clone the repository
```bash
git clone https://github.com/domckk/vital-link.git
```

## Large Dataset/File
Due to GitHub's file size limits, the required data files are available on Google Drive:

- [Download `Vital-Link.zip` from Google Drive](https://drive.google.com/drive/folders/13G1gldDqOA4AnGrrN8aXxthr57t4RskN?usp=drive_link)

After downloading, extract the zip file and open the file directly in your IDE.

## Setup Instructions

### Frontend Setup
1. Navigate to frontend directory:
   ```bash
   npm run dev
### Backend Setup
1. Navigate to frontend directory:
   ```bash
   cd backend
   pip install -r requirements.txt
   uvicorn main:app --reload

#### Dependencies to Install
1. Frontend
   ```bash
   cd frontend
   npm install

   npm install react react-dom axios @mui/material @emotion/react @emotion/styled
	 npm install -D tailwindcss postcss autoprefixer  
2. Backend
   ```bash
   cd backend
	 pip install -r requirements.txt
   pip install fastapi uvicorn python-dotenv
	 pip install numpy pandas transformers torch 
	 pip install sqlalchemy pymongo 

   
