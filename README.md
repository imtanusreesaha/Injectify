## 🛡️ SQL Injection Simulation Lab

---
## 🔍 Overview  
Welcome to  SQL Injection Simulation Lab – my personal simulation lab built to understand and demonstrate how SQL Injection vulnerabilities work in web applications.

As someone diving into the world of cybersecurity and ethical hacking, I wanted to create a simple yet practical tool to test and simulate SQLi attacks in a safe, controlled environment. This project showcases how insecure database queries can be exploited – and why it's so important to sanitize input.

**SQL Injection (SQLi)** is one of the most critical web vulnerabilities that allows attackers to interfere with queries made to a database. This project is a hands-on simulation lab designed to **demonstrate and understand SQL Injection vulnerabilities** in a safe, educational environment.

It showcases how malicious actors can exploit poorly secured login forms and URL parameters, helping students and beginners learn the importance of secure coding practices.

Whether you're a beginner or brushing up your skills,  SQL Injection Simulation Lab provides hands-on exposure to:

->Classic SQL injection via login forms

->Exploiting GET and POST requests

->Understanding how malicious payloads bypass security

---


**SQL Injection (SQLi)** is one of the most critical web vulnerabilities that allows attackers to interfere with queries made to a database. This project is a hands-on simulation lab designed to **demonstrate and understand SQL Injection vulnerabilities** in a safe, educational environment.

It showcases how malicious actors can exploit poorly secured login forms and URL parameters, helping students and beginners learn the importance of secure coding practices.

---

## 🎯 Features  
- 🔎 **Vulnerability Demonstration**: Simulates login-based SQL Injection scenarios.  
- 🧠 **Educational Purpose**: Ideal for learning web security and ethical hacking basics.  
- 🧪 **GET & POST Methods**: Shows injection possibilities through both types of HTTP requests.  
- 🔐 **Input Sanitization Awareness**: Highlights how lack of sanitization can compromise systems.  
- 📜 **Lightweight Design**: Built for local use via XAMPP, WAMP, or LAMP stacks.

---

## 🧠 Project Architecture  
**Base**: PHP + MySQL  
**Interface**: HTML/CSS  

**Functionalities**:
- User Login form  
- SQL vulnerable login verification logic  
- Exploitable through `' OR '1'='1` and similar payloads  

**Security Gaps** (Intentional for learning):  
- No input validation  
- Raw SQL query execution  

---

## 🗃️ Dataset  
No external datasets are used.  
Data is seeded into a **MySQL database** through the `database.sql` file provided.  
Contains sample user credentials for demonstration.

---

## 🧪 Demo Examples  
- `' OR '1'='1` – Logs in as any user  
- `' OR 1=1 -- ` – Bypasses password validation  
- `admin' -- ` – Forces login as admin  

> ⚠️ These are to be used **only inside this simulation** and not for malicious intent.

---

## 🧰 Tech Stack  

**Backend**:  
- PHP  
- MySQL  

**Frontend**:  
- HTML/CSS  

**Environment**:  
- XAMPP / WAMP / LAMP (Localhost)

---

## 📁 Folder Structure  
```
├── .settings/ # Project settings folder
├── WebContent/ # Web-related resources (HTML, JSP, etc.)
├── build/classes/ # Compiled Java classes
├── others/ # Additional tools/utilities
├── src/ # Java source code files
├── .classpath # Eclipse classpath configuration
├── .gitignore # Git ignored files
├── .project # Eclipse project configuration
└── README.md # Project documentation
```

## 🚀 Getting Started  

### Prerequisites  
- XAMPP or any local web server stack  
- PHP & MySQL installed  

### Steps  
1. Clone or download this repository  
2. Move the project folder to `htdocs/` in XAMPP  
3. Import `database.sql` using phpMyAdmin  
4. Start Apache & MySQL via XAMPP  
5. Visit `http://localhost/sql-injection-lab/` in your browser  
6. Try logging in with SQL payloads to observe the vulnerability

---

## 📸 Sample Output  
# Example
--------
### 🔒 Test with and without Protection:

1.Original Login Page
![Original Login Page](https://github.com/imtanusreesaha/SQL-Injection-Simulation-Lab/blob/main/SQL%20Injection%20Simulation%20Lab/test_orig.png?raw=true)

2. Test case 1 (without protection)<br/>
![alt test1](https://github.com/mndarren/SQL-Injection-Simulation-Project/blob/organize_code/others/test1.PNG)
3. Test case 2 (without protection)(password is the same to user name)<br/>
![alt test2](https://github.com/mndarren/SQL-Injection-Simulation-Project/blob/organize_code/others/test2.PNG)
4. Test case 3(without protection)<br/>
![alt test3](https://github.com/mndarren/SQL-Injection-Simulation-Project/blob/organize_code/others/test3.PNG)
5. Test case 5 (repeat 3 with protection)<br/>
![alt test5](https://github.com/mndarren/SQL-Injection-Simulation-Project/blob/organize_code/others/test5.PNG)
6. Test case 6 (repeat 2 with protection)<br/>
![alt test6](https://github.com/mndarren/SQL-Injection-Simulation-Project/blob/organize_code/others/test6.PNG)
7. Test case 7(repeat 4 with protection)<br/>
![alt test7](https://github.com/mndarren/SQL-Injection-Simulation-Project/blob/organize_code/others/test7.PNG)
8. Test case 8(Common user login)<br/>
![alt test8](https://github.com/mndarren/SQL-Injection-Simulation-Project/blob/organize_code/others/test8.PNG)

---

## 🔮 Future Improvements  
- Add safe version with **prepared statements** for comparison  
- Visualize attack flow with frontend alerts  
- Deploy as a teaching module for cybersecurity classes  
- Add logging to track injection attempts  

---

## 📜 License  
This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgments  
- OWASP Foundation  
- PortSwigger Web Security Academy  
- PHP Documentation  
- Ethical Hacking communities  

---

## 👩‍💻 Author  
**Tanusree Saha**  
GitHub: [Tanusree Saha](https://github.com/imtanusreesaha)  
Email: [imtanusreesahaa@gmail.com](mailto:imtanusreesahaa@gmail.com)

