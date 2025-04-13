# 🛡️ SQL Injection Simulation Lab

## 📌 Introduction  
This project is a beginner-friendly lab that simulates **SQL Injection vulnerabilities** in web applications. Built using **Java, JSP, and MySQL**, it demonstrates how insecure coding practices can expose login systems to malicious database queries. The simulation helps students, developers, and security enthusiasts understand the importance of secure coding and how to prevent common web attacks.

---

## 🔍 Overview  
SQL Injection is one of the most common application-layer attack vectors. This project creates a simple yet effective web application that allows users to simulate both vulnerable and secure login systems, observe how attacks work, and understand how to prevent them.

---

## 🧰 Tools & Technologies  
- **IDE**: Eclipse  
- **Backend**: Java (JSP/Servlet)  
- **Database**: MySQL  
- **Server**: Apache Tomcat  

---

## 🏗️ Project Architecture  
The system is divided into three layers:  
- **UI Layer**: Front-end login interface  
- **Logic Layer**: Handles request processing  
- **Database Layer**: Communicates with MySQL for credential validation  

# Architecture
-------------
Setting up 3 layers: UI, Logical, and DB<br/>
![alt architecture](https://github.com/mndarren/SQL-Injection-Simulation-Project/blob/master/others/architecture.PNG)

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

# 📁 Folder Structure

```

├── .settings/                # Project settings folder  
├── WebContent/               # Web-related resources (HTML, JSP)  
├── build/classes/            # Compiled Java classes  
├── others/                   # Screenshots & SQL scripts  
├── src/                      # Java source files (Servlets, Logic)  
├── .classpath                # Eclipse classpath config  
├── .gitignore                # Git ignored files  
├── .project                  # Eclipse project config  
└── README.md                 # Project documentation

```

# ⚙️ How to Run  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/mndarren/SQL-Injection-Simulation-Project.git

Import into Eclipse

Configure Database

Navigate to: WebContent/META-INF/context.xml

Update the MySQL connection string and credentials.

Run on Apache Tomcat Server

# 📝 Notes
MySQL scripts are available in the others/ folder.

Make sure MySQL is running and properly configured before starting the project.

The project is educational and should not be used in production environments.

# 📜 License
This project is intended for educational use only and is distributed under the MIT License.

