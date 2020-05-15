# Rail Analysis and Management System  

The **Rail Analysis and Management System** is a robust application designed to simplify and streamline railway operations, including schedule management, ticket booking, and user feedback collection. Built with Python and PyQt5 (PySide2), it features an intuitive GUI and implements advanced data structures and algorithms for efficient operations.  

## 🌟 Key Features  

### 1. **User Authentication and Signup**  
- **Secure Credentials**: User credentials are encrypted using the bcrypt library and stored in a local CSV database.  
- **Unique Identification**: Ensures unique usernames and email addresses to maintain secure user accounts.  

### 2. **Google Sign-In Integration**  
- **Convenience**: Seamless integration of Google sign-in via OAuth2.0 for quick and secure access.  
- **Asynchronous Processing**: Ensures a smooth and responsive user experience.  

### 3. **Railway Schedule Management**  
- **Dynamic Linked List**: Efficiently organizes railway schedules from the "Train and Time.csv" file.  
- **Interactive UI**: Includes sortable tables and dynamic combo boxes for user-friendly schedule filtering and exploration.  

### 4. **Booking Confirmation**  
- **Constraint Verification**: Verifies valid start and end locations to prevent invalid bookings.  
- **Transparent Pricing**: Automatically calculates ticket prices based on selected options.  

### 5. **Graph Visualization**  
- **NetworkX and Matplotlib**: Visualizes railway routes and connections using graph data from "graphAttributes.txt."  
- **Intuitive Representation**: Provides clear and interactive graph-based insights.  

### 6. **User Feedback Collection**  
- **Stack Implementation**: Stores user feedback in a stack structure, saved to "feedback.txt" for future analysis.  
- **Long-Term Accessibility**: Ensures organized and persistent feedback management.  

---

## 🛠️ Technologies Used  
- **Programming Language**: Python 3.9  
- **Framework**: PyQt5 (PySide2)  
- **Data Structures**: Linked List, Stack  
- **Visualization**: NetworkX, Matplotlib  
- **Database**: CSV  

---

## 🚀 Getting Started  

### Prerequisites  
Ensure you have **Python 3.9** installed. Update your environment variables as follows:  
```plaintext
C:\Users\<YourUsername>\AppData\Local\Programs\Python\Python39\Scripts\
C:\Users\<YourUsername>\AppData\Local\Programs\Python\Python39\
```  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yassin549/Rail-Analysis-and-Management
   cd Rail-Analysis-and-Management
   ```  

2. Install required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

3. Run the application:  
   ```bash
   python main.py
   ```  

---

## 📂 File Structure  

- **`main.py`**: Entry point of the application.  
- **`ui/`**: Contains `.ui` files for the GUI layout.  
- **`csv/`**: Stores CSV files for schedules and data management.  
- **`feedback.txt`**: File for storing user feedback.  
- **`graphAttributes.txt`**: Graph data for visualizing railway routes.  

---

## 📧 Contact  

For any questions or support, please reach out:  
- **Author**: Yassin Khoualdi  
- **Email**: [officialyassinkhoualdi@gmail.com](mailto:officialyassinkhoualdi@gmail.com)  

---

## 🎉 Future Enhancements  
- Add multi-user roles (e.g., Admin, User).  
- Implement a more advanced database system (e.g., MySQL or SQLite).  
- Expand graph visualization to include real-time updates.  

Transform your railway management with the **Rail Analysis and Management System**! 🚂  
