
# Three-Level Authentication System

Secure multi-factor authentication web application with password validation, image-based pattern recognition, and email OTP verification.

## 🚀 Features

- **Level 1:** Username and password authentication with bcrypt encryption
- **Level 2:** Image-based pattern recognition for additional security
- **Level 3:** One-Time Password (OTP) sent via email with timeout validation
- Account lockout after 3 failed login attempts
- Email notifications for security alerts and account recovery
- Responsive UI with real-time validation

## 🛠️ Tech Stack

**Frontend:**
- HTML5, CSS3, JavaScript
- Bootstrap for responsive design

**Backend:**
- Python
- Flask/FastAPI
- SMTP for email integration

**Database:**
- MySQL
- Bcrypt for password hashing

## 📋 Prerequisites

- Python 3.8+
- MySQL 5.7+
- Gmail account (for SMTP)

## ⚙️ Installation

1. Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/three-level-authentication.git
cd three-level-authentication
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Set up database
```bash
mysql -u root -p < database/schema.sql
```

4. Configure environment variables
```bash
cp .env.example .env
# Edit .env with your credentials
```

5. Run the application
```bash
python app.py
```

6. Open browser to `http://localhost:5000`


## 👥 Team

This project was developed as part of Software Engineering coursework by:
- [Richa Rameshkrishna](https://github.com/richa-ramesh)
- Pratheek Babu
- Rachitha S
- Apoorva Sarvade

**My Contributions:**
- OTP generation and email delivery system
- Database schema design
- Frontend UI for authentication flows

## 🔒 Security Features

- Password hashing with bcrypt (salt rounds: 10)
- Session management with secure tokens
- OTP expiration (5-minute timeout)
- Rate limiting on login attempts
- Account lockout mechanism

## 🚧 Future Improvements

- [ ] Add biometric authentication
- [ ] Implement 2FA with Google Authenticator
- [ ] Add CAPTCHA to prevent bot attacks
- [ ] Password reset via security questions
- [ ] Admin dashboard for user management

## 📄 License

MIT License - see LICENSE file for details

## 📧 Contact

Richa Rameshkrishna - richaramesh2002@gmail.com

LinkedIn: [linkedin.com/in/richa-ramesh](https://linkedin.com/in/richa-ramesh)
