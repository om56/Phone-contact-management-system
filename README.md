# Contact Book Management System (C++)

A simple **menu-driven Contact Book application** developed using **C++**.  
It allows users to add, view, search, update, and delete contacts with **file-based storage**.

## Features
- Add new contact
- View all contacts
- Search contact by name
- Update contact details
- Delete contact
- Data saved using file handling (`Contacts.txt`)

## Technologies Used
- C++
- OOP (Classes & Objects)
- STL (`vector`)
- File Handling (`fstream`)

## How It Works
- Contacts are stored in a vector during runtime
- Data is read from file at program start
- Updated data is written back to file on exit

## How to Run
```bash
g++ main.cpp -o app
./app
