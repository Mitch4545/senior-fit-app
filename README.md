# SeniorFit - AI-Powered Senior Fitness Plans

SeniorFit is a web application that generates personalized fitness plans for seniors using artificial intelligence. The application takes into account the user's age, health conditions, and fitness goals to create safe and effective exercise programs.

## Features

- User registration and authentication
- Personalized fitness plan generation using AI
- Health condition and fitness goal tracking
- Senior-friendly interface with large text and clear navigation
- Mobile-responsive design
- Secure data storage

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- OpenAI API key

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/senior-fit-app.git
cd senior-fit-app
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the project root and add your OpenAI API key:
```
OPENAI_API_KEY=your_api_key_here
SECRET_KEY=your_secret_key_here
```

## Running the Application

1. Initialize the database:
```bash
flask db init
flask db migrate
flask db upgrade
```

2. Start the Flask development server:
```bash
python app.py
```

3. Open your web browser and navigate to `http://localhost:5000`

## Usage

1. Register a new account with your personal information
2. Log in to your account
3. Update your profile with health conditions and fitness goals
4. View your personalized fitness plan on the dashboard
5. Update your profile anytime to generate a new fitness plan

## Safety Guidelines

- Always consult with your healthcare provider before starting any new exercise program
- Start slowly and gradually increase intensity
- Listen to your body and stop if you experience any pain or discomfort
- Stay hydrated during exercise
- Exercise in a safe environment with proper lighting and support

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 