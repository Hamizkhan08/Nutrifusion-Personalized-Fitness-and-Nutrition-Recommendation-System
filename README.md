# Nutrifusion-Personalized-Fitness-and-Nutrition-Recommendation-System

## Overview
Nutrifusion is a personalized fitness and nutrition recommendation system designed to provide users with customized workout and diet plans based on their inputs. The system leverages machine learning (Random Forest) to generate optimal fitness and nutrition suggestions tailored to the user's needs.

## Features
- **User Authentication**: Login and Registration using MySQL (phpMyAdmin via XAMPP)
- **Personalized Recommendations**:
  - Workout plans based on muscle difficulty level and workout type
  - Nutrition plans tailored to individual needs
- **Machine Learning Integration**: Random Forest for generating recommendations
- **Frontend**: HTML, CSS (Flask-powered UI)
- **Backend**: Python (Flask, Pandas, NumPy)
- **Database**: MySQL (via XAMPP)
- **Deployment**: Free and reliable hosting options (to be determined)

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Python (>=3.8)
- Flask
- Pandas
- NumPy
- MySQL (phpMyAdmin via XAMPP)

### Steps to Run the Project
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/Nutrifusion.git
   cd Nutrifusion
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Start MySQL in XAMPP and create a database `nutrifusion_db`.
4. Import the provided SQL file into phpMyAdmin to set up tables.
5. Run the Flask application:
   ```sh
   python app.py
   ```
6. Open `http://127.0.0.1:5000/` in your browser.
7. 
## Usage
1. Register or log in.
2. Enter required inputs (height, weight, workout type, muscle difficulty level, etc.).
3. Receive a personalized fitness and nutrition plan.

## Future Enhancements
- Improve UI/UX
- Add more ML models for better recommendations
- Implement API for mobile integration
- Deploy project on a cloud platform

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact: **Hamiz Khan**

---
*Nutrifusion: Your AI-powered fitness and nutrition guide!*

