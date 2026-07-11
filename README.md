# Linux-Office-Management-System


A beginner-friendly **Menu-Driven Bash Shell Project** that demonstrates Linux Administration concepts such as **User Management**, **Group Management**, **Password Management**, **File Permissions**, **Vim File Operations**, and **Backup Management**.

This project is designed for students who are learning Linux shell scripting and basic system administration. It provides a simple command-line interface to perform common administrative tasks while practicing essential Linux commands.



## 📌 Features

- 📄 Add Employee Records using Vim Editor
- 👀 View Employee Records
- 👤 Create Linux Users
- 🔐 Set User Passwords
- 👥 Create Linux Groups (Departments)
- ➕ Add Users to Groups
- 🔒 Change File Permissions
- 💾 Backup Employee Records
- 📂 Display Current Working Directory
- 📋 List All Linux Users
- 📑 List All Linux Groups
- 🚪 Exit Program



## 🎯 Learning Objectives

This project helps you understand:

- Bash Shell Scripting
- Menu-driven programming
- Vim editor
- File handling in Linux
- User Management
- Group Management
- Password Management
- File Permissions
- Linux Commands
- Backup using Shell Script






# 🛠 Technologies Used

- Bash Shell
- Linux
- Vim Editor
- GNU Core Utilities



# 📋 Prerequisites

Before running the project, make sure your system has:

- Linux (Ubuntu/CentOS/Fedora/Kali)
- Bash Shell
- Vim Editor
- sudo privileges



# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Linux-Office-Management-System.git
```

Go to project folder

```bash
cd Linux-Office-Management-System
```

Give execute permission

```bash
chmod +x office.sh
```

Run the project

```bash
./office.sh
```



# 📖 Menu

```
===========================================
      LINUX OFFICE MANAGEMENT SYSTEM
===========================================

1. Add Employee Record
2. View Employee Records
3. Create Linux User
4. Set User Password
5. Create Department
6. Add User to Department
7. Change File Permission
8. Backup Employee Records
9. Show Current Directory
10. List Linux Users
11. List Groups
12. Exit

===========================================
```


# 📌 Feature Explanation

## 1️⃣ Add Employee Record

Creates employee records using the Vim editor.

Example

```
Employee ID : 101
Name : Snehal Late
Department : IT
Salary : 25000
```



## 2️⃣ View Employee Record

Displays saved employee information.

Uses:

```
cat
```



## 3️⃣ Create Linux User

Creates a new Linux user.

Command used

```bash
sudo useradd username
```



## 4️⃣ Set User Password

Assigns a password to an existing Linux user.

Command

```bash
sudo passwd username
```


## 5️⃣ Create Department

Creates a Linux Group.

Command

```bash
sudo groupadd groupname
```



## 6️⃣ Add User to Department

Adds an existing user to a Linux group.

Command

```bash
sudo usermod -aG groupname username
```



## 7️⃣ Change File Permission

Changes file permissions using chmod.

Example

```bash
chmod 755 employee.txt
```



## 8️⃣ Backup Employee Records

Copies all employee files into the Backup directory.

Command

```bash
cp -r Employees Backup
```



## 9️⃣ Show Current Directory

Displays the current working directory.

Command

```bash
pwd
```



## 🔟 List Linux Users

Displays all users from

```
/etc/passwd
```



## 1️⃣1️⃣ List Groups

Displays all Linux groups from

```
/etc/group
```


## 🧑‍💻 Commands Used

| Command | Purpose |
|----------|----------|
| mkdir | Create Directory |
| cd | Change Directory |
| pwd | Print Working Directory |
| touch | Create File |
| vim | Edit File |
| cat | View File |
| chmod | Change Permissions |
| cp | Backup Files |
| ls | List Files |
| sudo useradd | Create User |
| sudo passwd | Set Password |
| sudo groupadd | Create Group |
| sudo usermod | Add User to Group |



# 📷 Screenshots

Add screenshots inside the **screenshots** folder.

Example

- Main Menu
- Add Employee
- User Creation
- Password Creation
- Backup
- Permission Change



# 💡 Future Improvements

- Employee Search
- Employee Delete
- Employee Update
- Attendance Management
- Login Authentication
- CSV Export
- Colored Terminal Output
- Logging System
- Error Handling
- Employee Reports



# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Push the branch
5. Open a Pull Request

