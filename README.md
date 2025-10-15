\# 📚 Library Management System



A backend system built using \*\*Java Spring Boot\*\* and \*\*MySQL\*\* to manage library operations such as book borrowing, user management, and authentication.  

This project demonstrates best practices in \*\*REST API design\*\*, \*\*clean architecture\*\*, and \*\*modular backend development\*\*.



---



\## 🚀 Tech Stack

\- \*\*Language:\*\* Java 17  

\- \*\*Framework:\*\* Spring Boot  

\- \*\*Database:\*\* MySQL  

\- \*\*Security:\*\* Spring Security, JWT Authentication  

\- \*\*Build Tool:\*\* Maven  

\- \*\*Version Control:\*\* Git \& GitHub  



---



\## ⚙️ Features

✅ User authentication and authorization using JWT  

✅ Role-based access for admins, librarians, and users  

✅ Book issue and return tracking  

✅ Real-time updates for available books  

✅ Error handling with custom exceptions  

✅ RESTful API design with proper status codes  



---



\## 🧠 Architecture Overview

This project follows the \*\*MVC (Model-View-Controller)\*\* and \*\*Service-Oriented Architecture\*\* design patterns for scalability and maintainability.  



\*\*Layers:\*\*

\- \*\*Controller:\*\* Handles incoming REST requests  

\- \*\*Service:\*\* Business logic layer  

\- \*\*Repository:\*\* Communicates with the MySQL database  



---



\## 🧩 API Endpoints (Examples)

| Method | Endpoint | Description |

|--------|-----------|-------------|

| `POST` | `/api/auth/login` | User login |

| `POST` | `/api/books` | Add a new book (Admin only) |

| `GET` | `/api/books` | Get all available books |

| `PUT` | `/api/books/{id}` | Update book details |

| `DELETE` | `/api/books/{id}` | Delete a book (Admin only) |



---



\## 📅 Timeline

Developed: \*\*October 2025\*\*  

Status: \*\*Work in progress / Planned expansion\*\*



---



\## 🧰 How to Run Locally

```bash

\# Clone this repository

git clone git@github.com:HarshaVardhan-49/library-management-system.git



\# Navigate into the folder

cd library-management-system



\# Build and run the application

mvn spring-boot:run

