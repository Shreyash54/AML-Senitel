# AML Sentinel - Anti-Money Laundering Detection System

AML Sentinel is a robust, AI-powered platform designed to detect and analyze suspicious financial transactions. It leverages machine learning for anomaly detection and LLMs (Large Language Models) for automated generation of Suspicious Activity Reports (SAR).

##  Features

- **Advanced Transaction Analysis**: Detects patterns like Structuring, Money Mule activity, and Round Tripping.
- **AI-Powered Risk Scoring**: Uses an Anomaly Detection model (Isolation Forest) to rank transaction risks.
- **Automated SAR Generation**: Integrates with LLMs (via Groq/LangChain) to generate detailed reports automatically.
- **Interactive Dashboard**: Real-time visualization of transaction trends and risk profiles using Recharts.
- **Bulk Data Handling**: Support for large-scale transaction uploads via CSV.
- **Secure Authentication**: Implements JWT-based auth and Google OAuth integration.

## Tech Stack

### Backend
- **Framework**: Django 4.2+ & Django REST Framework (DRF)
- **Database**: SQLite3 (Development)
- **Machine Learning**: Scikit-Learn (Isolation Forest)
- **LLM Orchestration**: LangChain & Groq API


### Frontend
- **Framework**: React 18+ (Vite)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Charts**: Recharts
- **State Management**: React Context API

##  Prerequisites

- **Python**: 3.9+
- **Node.js**: 18+
- **Groq API Key**: Required for AI analysis and SAR generation.

##  Setup & Installation

### 1. Clone the Project
```bash
git clone <repository-url>
cd aml-sentinel/attempt
```

### 2. Backend Setup
Create and activate a virtual environment:
```bash
python -m venv venv
# Windows
.\venv\Scripts\activate
# Linux/macOS
source venv/bin/activate
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Set up environment variables:
Create a `.env` file in the `attempt` directory with:
```env
GROQ_API_KEY=your_groq_api_key
DJANGO_SECRET_KEY=your_secret_key
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```

Run migrations:
```bash
python manage.py migrate
```

Train the initial ML model:
```bash
python manage.py train_model
```

### 3. Frontend Setup
Navigate to the frontend directory:
```bash
cd aml_frontend
npm install
```

##  Running the Application

### Start Backend
In the `attempt` directory:
```bash
python manage.py runserver
```
The backend will be available at `http://127.0.0.1:8000/`.

### Start Frontend
In the `aml_frontend` directory:
```bash
npm run dev
```
The application will be accessible at `http://localhost:5173/`.

##  Testing

To run the full application test suite:
```bash
python test_full_app.py
```

## By 
Shreyash Gupta 
Akshay Patil
Om Salunkhe
Shivam Patidar
Subhaan jiraat
Alfeen Khan

<img width="896" height="884" alt="image" src="https://github.com/user-attachments/assets/8efa3f6a-b617-4a48-b49b-ce2e60d725dd" />
<img width="1886" height="898" alt="image" src="https://github.com/user-attachments/assets/a9aadf38-6eb4-4c62-b139-d299db3af6f4" />
<img width="1888" height="1050" alt="image" src="https://github.com/user-attachments/assets/1df171a9-d2b8-4e19-a64d-a715e988cc23" />
<img width="1873" height="905" alt="image" src="https://github.com/user-attachments/assets/5640c9a9-e6ef-4357-b35c-b0ee3437e6f9" />
<img width="1858" height="1426" alt="image" src="https://github.com/user-attachments/assets/0221d6bc-032e-47bf-9eef-e1337cde51f7" />
<img width="1819" height="1031" alt="image" src="https://github.com/user-attachments/assets/e9bcbced-b840-40b0-9472-0b5792636583" />
<img width="1845" height="1185" alt="image" src="https://github.com/user-attachments/assets/d5096d9d-bae5-4ac2-9d81-b4dd3938cb89" />
<img width="1675" height="940" alt="image" src="https://github.com/user-attachments/assets/b81a260f-8b7e-4268-83d3-e1439e5eee6e" />
<img width="1652" height="962" alt="image" src="https://github.com/user-attachments/assets/c0cc3a71-3a68-4292-8183-48cc88de75ae" />
<img width="1442" height="1049" alt="image" src="https://github.com/user-attachments/assets/298dc9c9-9418-4e54-b375-6380ae850ffd" />
<img width="1574" height="849" alt="image" src="https://github.com/user-attachments/assets/0317b09f-64aa-44e9-ac4c-010c3d11091f" />
