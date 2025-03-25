# Complaint Management System

## Overview
The **Complaint Management System** is a Python-based project designed to efficiently handle complaints from users. It allows users to register complaints, track their status, and administrators to resolve them. This system can be used in organizations, customer service departments, and institutions to streamline complaint handling.

## Features
- User Registration and Login
- Complaint Submission with Category Selection
- Complaint Tracking by Users
- Admin Panel for Complaint Management
- Status Updates and Resolution Tracking

## Technologies Used
- **Backend:** Python (Tkinter for GUI)
- **Database:** SQLite
- **Authentication:** User Login System

## Installation
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/Complaint-Management-System.git
   cd Complaint-Management-System
   ```
2. **Run the Application**
   ```sh
   python main.py
   ```

## Usage
### Running the GUI Application
The application is built using Tkinter, a built-in Python GUI library. To run the system:
1. Open a terminal or command prompt in the project folder.
2. Run the following command:
   ```sh
   python main.py
   ```
3. The complaint management window will open where users can:
   - Enter their **Full Name**
   - Select their **Gender**
   - Type their **Complaint**
   - Click **Submit Now** to save the complaint
   - Click **List Comp.** to view submitted complaints

## Folder Structure
```
Complaint-Management-System/
│-- main.py             # Main Application
│-- db.py               # Database Management
│-- listComp.py         # Complaint Listing Module
│-- information         # Database File
│-- Readme              # Project Documentation
│-- __pycache__/        # Compiled Python Files
```

## Future Enhancements
- Implementing AI-based Complaint Prioritization
- Adding Multi-Tenant Support
- Mobile App Integration

## License
This project is licensed under the MIT License.

## Contributing
Feel free to submit issues or pull requests to improve the system.

## Contact
For any queries, reach out to [your-email@example.com].

