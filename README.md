# Iscternship

Iscternship is a web platform for managing internships, connecting candidates and companies, and facilitating the application and review process.

Login                                                                                                    |  Role's List
:-------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:
![image](https://github.com/user-attachments/assets/4f2d9cae-37e1-4a51-b4da-5f2dc2adc045)                |  ![image](https://github.com/user-attachments/assets/571f23a4-b20f-44de-9810-57091a5a1b15)

## Project Structure

```
.
├── backend_iscternship/      # Django backend (API, database, admin)
├── frontend_iscternship/     # React frontend (user interface)
├── Instructions.txt          # Setup instructions
├── DIAM_RelatorioProjeto_Iscternship.pdf # Project report
└── ...
```

## Features

- Candidate and company registration and authentication
- Internship (vaga) management and applications
- Review system for candidates and companies
- CV upload and management
- Admin dashboard for managing users and offers
- AI-powered CV review using Google Gemini API

## Technologies

- **Frontend:** React, Bootstrap, Framer Motion, Axios
- **Backend:** Django, SQLite, Pillow, PyMuPDF
- **AI Integration:** Google Generative AI (Gemini)

## Setup Instructions

### Backend

1. Navigate to the backend directory:
    ```sh
    cd backend_iscternship
    ```
2. Install dependencies:
    ```sh
    pip install Pillow PyMuPDF
    ```
3. Run the server:
    ```sh
    python manage.py runserver
    ```

### Frontend

1. Navigate to the frontend directory:
    ```sh
    cd frontend_iscternship
    ```
2. Install dependencies:
    ```sh
    npm install
    npm install bootstrap react-router-dom axios moment framer-motion @react-google-maps/api @google/generative-ai
    ```
3. Start the development server:
    ```sh
    npm start
    ```

### Environment Variables

- Create a `.env` file in `frontend_iscternship/` and add your Google Gemini API key:
    ```
    REACT_APP_GEMINI_API_KEY=your_google_gemini_api_key
    ```

## Folder Details

- **backend_iscternship/db_iscternship/**: Django app with models for candidates, companies, reviews, and offers.
- **frontend_iscternship/src/**: React components, pages, and styles.

## License

This project is for academic purposes.

---

For more details, see [Instructions.txt](Instructions.txt) and the project report.
