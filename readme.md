# Bash-DBMS

A simple, interactive database management system implemented entirely in **Bash**.

## 🧰 Features

- Create and drop databases  
- Create and drop tables within databases  
- Insert, delete, update, and select records  
- Add new columns and check for duplicates  
- Enforce simple primary-key checks for uniqueness  
- Menu-driven shell interface for easy use  

## 📂 Project Structure

```
.
├── .gitignore
├── GetAllDbs
├── connectToDB
├── createDB
├── dropDB
├── createTable
├── deleteTable
├── addTableColumn
├── checkForRepeatedColumnName
├── getColumnIndex
├── getType
├── inputValidator
├── insertToTable
├── selectFromTable
├── getRows
├── deleteFromTable
├── updateInTable
├── databaseActions
├── main
└── pkCheck
```

Each file is a Bash script responsible for a specific functionality of the DBMS.

## 🚀 Getting Started

### Prerequisites
- Linux or macOS (or any Unix-like system)
- Bash 4.x or higher
- Basic permissions to create and modify files

### Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Abdelaziz-Gbr/Bash-DBMS.git
   cd Bash-DBMS
   ```

2. Make the scripts executable:
   ```bash
   chmod +x *
   ```

3. Run the main program:
   ```bash
   ./main
   ```

4. Follow the on-screen menu to create databases, tables, and records.

## 🧪 Example Session

```text
Welcome to Bash-DBMS!
1) Create Database
2) Connect to Database
3) List Databases
4) Drop Database
Enter choice: 1
Enter database name: mydb

Database “mydb” created.
```

Then inside the database:

```text
1) Create Table
2) Show Tables
3) Connect to Table
4) Drop Table
Enter choice: 1
Enter table name: users
Enter number of columns: 3
Enter column-1 name: id
Enter column-1 type (int/string): int
Enter column-2 name: name
Enter column-2 type (string): string
Enter column-3 name: age
Enter column-3 type (int/string): int

Table “users” created.
```

## ✅ Why This Project Is Useful

- Great for learning how databases work behind the scenes  
- Demonstrates how to simulate CRUD operations using Bash  
- Lightweight and doesn’t require installing any DBMS  
- Perfect for DevOps or Linux scripting practice  

## 🛠️ Future Enhancements

- Add JOIN functionality between tables  
- Support WHERE clauses with multiple conditions  
- Implement backup and restore  
- Improve input validation and error handling  
- Add color and improved UI  

## 👥 Contributing

Contributions are welcome!

1. Fork the repository  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit your changes (`git commit -m "Add new feature"`)  
4. Push the branch (`git push origin feature-name`)  
5. Open a Pull Request  

## 📄 License

This project is open source and free to use, modify, or distribute.

---

Thank you for using **Bash-DBMS**!  
Made with ❤️ by **Abdelaziz Gbr**
