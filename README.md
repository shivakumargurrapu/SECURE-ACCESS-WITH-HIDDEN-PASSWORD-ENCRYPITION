# 📌 Secure Access With Hidden Password Encryption
### Java | JSP | Servlets | MySQL | Tomcat

## 📖 Overview
Secure Access With Hidden Password Encryption is an advanced authentication system that uses the Encrypted Negative Password (ENP) technique to protect user passwords against:

- Dictionary Attacks
- Rainbow Table Attacks
- Lookup Table Attacks
- Brute Force Attacks

This system enhances traditional password protection using:

1. SHA-256 Hashing
2. Negative Password Generation
3. AES Symmetric Encryption
4. Multi-Iteration Encryption

## ✨ Features
### 🔐 Strong Password Protection  
- Plain password → Hash → Negative Password → AES Encrypted  
- Resistant to precomputed attacks  
- No salts required  

### 👤 Multi-User Roles  
- End User  
- Data Owner  
- Web Server Admin  

### 📁 Secure File Access  
- Users request access  
- Owner approves or rejects  
- Attacker tracking enabled  

## 🛠️ Technologies Used
| Layer | Technology |
|------|-------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Java, JSP, Servlets |
| Database | MySQL |
| Server | Apache Tomcat |
| Encryption | SHA-256, AES |

## 📂 Project Structure
```
/SecureAccess
│
├── /WebContent
├── /src
└── README.md
```

## 🔧 Installation & Setup

### 1. Clone Repository  
```
git clone https://github.com/shivakumargurrapu/Secure-Access-Encryption.git
```

### 2. Create MySQL Database  
```
CREATE DATABASE secure_access;
```

### 3. Configure Database  
```
DB_URL = jdbc:mysql://localhost:3306/secure_access
DB_USER = root
DB_PASS = root
```

### 4. Deploy on Tomcat  
Place project folder in `tomcat/webapps/` and start the server.

### 5. Access Application  
```
http://localhost:8080/SecureAccess/
```

## 🔑 ENP Algorithm Workflow
1. SHA-256 hashing  
2. Negative password generation  
3. AES encryption  
4. Store final ENP in database  

## 🧪 Testing
- Functional Testing  
- Login Security  
- File Access  
- Attacker Simulation  

## 🔮 Future Enhancements
- Spring Boot migration  
- JWT authentication  
- REST API  
- Cloud deployment  

## 👨‍💻 Developer
**Gurrapu Shiva Kumar**  
MCA – Aurora’s PG College (2023–2025)
