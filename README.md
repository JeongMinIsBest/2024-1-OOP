# 🖥️ Object-Oriented Programming Final Project (Spring 2024)
This repository contains a collection of projects submitted for the **Object-Oriented Programming Final Project** during the **Spring 2024 semester**.
The repository consists of **five projects**, each demonstrating practical applications of **object-oriented programming concepts using Java**.
<br/>
<br/>

## 📂 Project Implementations
  
### Project 1 — Shape Class Implementation
- Defined a `Shape` interface and implemented it with `Circle`, `Oval`, and `Rect` classes  
- Each shape provides:
  - `draw()` method to display shape information
  - `getArea()` method to calculate the area
<br/>

### Project 2 — Customer Point Management Program
- Managed customer points using `HashMap<String, Integer>`  
- Supports:
  - Adding points with `addPoints()`
  - Viewing points per customer with `printCustomerPoints()`
- Program runs based on user input via `Scanner`
<br/>

### Project 3 — File Explorer
- Implemented a `FileExplorer` class to display files and directories within a specified directory (e.g., `C:\`)  
- The `listFiles()` method distinguishes files and folders and prints them to the console
<br/>

### Project 4 — GUI String Movement Program
- Built a Swing-based GUI using `JFrame` to display the string **"Love Java"**  
- Implemented keyboard input handling using `KeyListener` to move the string  
- Applied `Font` and `JLabel` for visual styling
<br/>

### Project 5 — Client-Server Time Communication Program
- **TimeServer**:
  - Opens a server socket and sends the current time to clients  
- **TimeClient**:
  - Connects to the server and prints the received time  
- Implemented using:
  - `Socket`, `ServerSocket`, `BufferedReader`, and `PrintWriter`
<br/>
<br/>

## ✅ How to Run

All source code files are located in the `src` directory and can be executed in a standard JDK environment.

1. **Compile**
```
javac FileName.java
```

2. **Run**
```
java ClassName
```
<br/>
<br/>
