# CLI Calendar Project

Welcome to my CLI-based calendar project! This Python program allows users to navigate dates, manage events with ease using natural language, and import/export event data through CSV files—all from the command line.

## Features

- **Navigate Between Dates**: Effortlessly move between months and years, or jump to specific dates.
- **Switch Views**: Toggle between month and year views for different calendar perspectives.
- **Smart Event Management**: Add, remove, edit, and view events using plain language. No strict syntax required!
- **CSV Import/Export**: 
  - Export: The program creates an `events.csv` file in the current working directory if one doesn't already exist.
  - Import: Reads a provided `events.csv` file specified through CLI arguments, ensuring seamless data flow.
- **First-Time Setup**: Automatically creates `events.csv` on first run if not present, ensuring a smooth start.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
```bash
python Calendar.py [optional events csv file]
```

**Warning:**
Setup your own openai api key as an environment varibale before running the code otherwise you will get an error.


https://github.com/user-attachments/assets/ab3cb136-0119-41a5-a849-d98d5ec69226


1. For Windows:
   ```bash
   setx OPENAI_API_KEY "your_api_key_here"
   ```
2. For Macos/Linux:
   ```bash
   export OPENAI_API_KEY="your_api_key_here"
   ```
