# C# ASP.NET Core MVC & WebAPI – Teacher Management App

## Project: Cumulative Assignment – Part 2  
By: Christine Bittle  
Author: Chait Gehi

This project is a continuation of a cumulative ASP.NET Core application that interacts with a MySQL database to perform CRUD (Create, Read, Update, Delete) operations on a Teachers table. Part 2 of the assignment focuses on the Add and Delete functionality using Web API and MVC.

---

## 📌 Features (MVP)

✅ Create, Read, Update, and Delete operations for Teachers  
✅ RESTful API for interacting with the database  
✅ Server-rendered Razor Views for form handling  
✅ Web page to add a new Teacher  
✅ Web page to confirm deletion of a Teacher

---

## 🗂 Project Structure

| Type       | Description                                    | File Location                           |
|------------|------------------------------------------------|------------------------------------------|
| DbContext  | Connects to MySQL database                     | `/Models/SchoolDbContext.cs`            |
| API Controller | Adds and deletes teachers via API            | `/Controllers/TeacherAPIController.cs`  |
| MVC Controller | Manages teacher page routes and views        | `/Controllers/TeacherPageController.cs` |
| Model      | Represents a Teacher object                    | `/Models/Teacher.cs`                    |
| View       | Page to add a new teacher                      | `/Views/Teacher/New.cshtml`             |
| View       | Page to confirm teacher deletion               | `/Views/Teacher/DeleteConfirm.cshtml`   |

---

## 🧪 Testing Requirements

Evidence of the following should be included in the submission (screenshots, cURL commands, etc.):

- ✅ POST request to add a teacher using the API
- ✅ DELETE request to remove a teacher via the API
- ✅ Functional web form to enter new teacher details
- ✅ Confirmation page for deleting a teacher

---

## 📝 Documentation Requirements

- ✅ Summary blocks for all API methods
- ✅ Well-named variables and methods for clarity
- ✅ XML comments for Teacher model properties
- ✅ This README.md file to document the project and submission

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
