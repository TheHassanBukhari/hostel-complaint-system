# Hostel Complaint System

This repository contains my first semester Python project, a Hostel Complaint Management System. It's a console based application that lets hostel residents submit complaints with categories and details, while administrators review, track, and resolve them. The project demonstrates Python fundamentals such as functions, file handling, and simple data structures.

**Project Type:** University Project (Solo) <br>
**Course:** ICT, 1st Semester, COMSATS University Islamabad

**Portfolio:** [hassanbukhari.is-a.dev](https://hassanbukhari.is-a.dev/) <br>
**LinkedIn:** [Syed Hassan Ali Bukhari](https://www.linkedin.com/in/syedhassanalibukhari/)

## Features

- Submit complaints with name, room number, category, subcategory, and description
- Complaint categories: Food, Water, Electricity, Internet, Maintenance, and Others
- Automatic serial numbers for each complaint
- Persistent storage as text files in a structured `Data/complaints` folder
- Admin panel (password protected): view unresolved complaints, view detailed complaint files, mark complaints resolved, view resolved list
- File based tracking using `complaint_index.txt` and `resolved_complaints.txt`

## How to Run

```bash
git clone https://github.com/TheHassanBukhari/hostel-complaint-system.git
cd hostel-complaint-system
python Project.py
```

> The program will automatically create a `Data` folder and required text files on the first run.

## Learning Outcomes

- Functions for modular programming
- File handling for complaint submission and storage
- Basic admin system with password protection
- Data persistence using plain text files
- Menu-driven console application in Python

## Admin Access

Admin panel is protected with a password. Default password: `admin123`

## Additional Resources

[Full Project Explanation](https://thehassanbukhari.github.io/hostel-complaint-system/)

## Author

[Syed Hassan Ali Bukhari](https://hassanbukhari.is-a.dev/)

## License

This project is licensed under the [MIT License](./LICENSE).
