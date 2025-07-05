# Parking Spot Recommender (PS Reco)

A modern web-based parking spot recommender system built with Python Flask, Tailwind CSS, DaisyUI, and SQLite.

## Features

- **Homepage:** Modern, attractive UI with project highlights
- **About Us:** Meet the creator and learn about the motivation behind PS Reco
- **User Authentication:** Signup, login, and logout using secure password hashing
- **Dashboard:** Placeholder for future parking spot recommendations (coming soon)
- **Responsive Design:** Styled with Tailwind CSS and DaisyUI for mobile and desktop

## About Us

**Purab**

Hi! I'm Purab, a 10th standard student passionate about technology and building real-world solutions. I love working with Python and Flutter, and enjoy learning new frameworks and tools to solve interesting problems.

This project, Parking Spot Recommender (PS Reco), was created as part of a hackathon challenge. My goal is to make parking smarter and more efficient for everyone, using modern web technologies and a user-friendly design. I believe that even as a student, it's possible to build impactful applications that address everyday challenges.

I'm always eager to learn, collaborate, and innovate. Thank you for checking out PS Reco!

## Technology Stack

| Component           | Technology/Library      |
|---------------------|------------------------|
| Backend Framework   | Flask                  |
| Frontend Styling    | Tailwind CSS, DaisyUI  |
| Database            | SQLite                 |
| Authentication      | Flask-Login            |

## Getting Started

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd psreco
```

### 2. Create a virtual environment (recommended)
```bash
python -m venv venv
# Activate on Windows:
venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the app
```bash
python app.py
```

The app will be available at [http://127.0.0.1:5000](http://127.0.0.1:5000)

## Project Structure

```
psreco/
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── about.html
│   ├── signup.html
│   ├── login.html
│   └── dashboard.html
└── venv/ (optional, not tracked)
```

## Future Extensions
- Real-time parking spot recommendations
- Color-coded spot availability (green = available, red = occupied)
- User preferences and parking history
- Integration with ML/computer vision for detection

## License
MIT License
