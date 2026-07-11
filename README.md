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



# Output

## Main Menu

```text
==================================================
        LINUX OFFICE MANAGEMENT SYSTEM
==================================================

1. Add Employee Record
2. View Employee Records
3. Create Linux User
4. Set User Password
5. Create Department (Group)
6. Add User to Department
7. Change File Permission
8. Backup Employee Records
9. Show Current Directory
10. List Linux Users
11. List Linux Groups
12. Exit

Enter your choice:
```

---

## 1. Add Employee Record

```text
Enter your choice: 1

Enter Employee File Name: Snehal
```

After entering the file name, the Vim editor opens.

Example employee record:

```text
-----------------------------------------
Employee ID   : 101
Name          : Snehal Bharat Late
Department    : Information Technology
Designation   : Software Engineer
Salary        : 25000
Phone         : 9876543210
Email         : snehal@example.com
-----------------------------------------
```

Save the file using:

```text
Esc
:wq
```

---

## 2. View Employee Record

```text
Enter your choice: 2

Employee Files

Snehal.txt
Rahul.txt

Enter file name: Snehal
```

Output

```text
-----------------------------------------
Employee ID   : 101
Name          : Snehal Bharat Late
Department    : Information Technology
Designation   : Software Engineer
Salary        : 25000
Phone         : 9876543210
Email         : snehal@example.com
-----------------------------------------
```

---

## 3. Create Linux User

```text
Enter your choice: 3

Enter Username: rahul

User created successfully.
```

---

## 4. Set User Password

```text
Enter your choice: 4

Enter Username: rahul

New password:
Retype new password:
passwd: password updated successfully
```

---

## 5. Create Department (Group)

```text
Enter your choice: 5

Enter Group Name: Developers

Group created successfully.
```

---

## 6. Add User to Department

```text
Enter your choice: 6

Enter Username: rahul
Enter Group Name: Developers

User added to Developers successfully.
```

---

## 7. Change File Permission

```text
Enter your choice: 7

Employee Files

Snehal.txt

Enter File Name: Snehal
Enter Permission (Example 755): 755

Permission Updated Successfully.
```

---

## 8. Backup Employee Records

```text
Enter your choice: 8

Creating Backup...

Backup Created Successfully.

Location:
Backup/Employees/
```

---

## 9. Show Current Directory

```text
Enter your choice: 9

/home/snehal/Linux-Office-Management-System
```

---

## 10. List Linux Users

```text
Enter your choice: 10

root
daemon
bin
sys
rahul
snehal
```

---

## 11. List Linux Groups

```text
Enter your choice: 11

root
sudo
users
developers
docker
```

---

## 12. Exit

```text
Enter your choice: 12

Thank you for using Linux Office Management System.
Have a Nice Day!
```




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

