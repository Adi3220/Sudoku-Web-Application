# Sudoku Solver Web Application

This is a web-based Sudoku solver application implemented in Java using Servlets and JSP.

## Tech Stack

-   **Programming Language:** Java
-   **Framework:** Java Servlet
-   **Front-end:** JSP (JavaServer Pages), CSS
-   **Database:** MySQL
-   **Build Tool:** Maven
-   **IDE:** Eclipse

## Features

-   User registration and login
-   Sudoku puzzle input and solver
-   Responsive user interface

## Project Structure

```
SUDOKU-adit
├── .classpath
├── .project
├── .settings/
│   ├── org.eclipse.core.resources.prefs
│   ├── org.eclipse.jdt.core.prefs
│   ├── org.eclipse.wst.common.component
│   ├── org.eclipse.wst.common.project.facet.core.xml
│   ├── org.eclipse.wst.jsdt.ui.superType.container
│   └── org.eclipse.wst.jsdt.ui.superType.name
├── build/
│   └── classes/
│       └── com/
│           └── sudoku/
│               ├── controller/
│               │   ├── GameServlet.class
│               │   ├── LoginServlet.class
│               │   └── RegisterServlet.class
│               └── model/
│                   ├── SudokuSolver.class
│                   └── User.class
└── src/
    └── main/
        ├── java/
        │   └── com/
        │       └── sudoku/
        │           ├── controller/
        │           │   ├── GameServlet.java
        │           │   ├── LoginServlet.java
        │           │   └── RegisterServlet.java
        │           └── model/
        │               ├── SudokuSolver.java
        │               └── User.java
        └── webapp/
            ├── game.jsp
            ├── index.jsp
            ├── login.jsp
            ├── register.jsp
            ├── META-INF/
            │   └── MANIFEST.MF
            ├── WEB-INF/
            │   ├── web.xml
            │   └── lib/
            │       ├── jstl-1.2.jar
            │       └── mysql-connector-j-8.3.0.jar
            └── css/
                └── style.css
```

## Setup

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/yourusername/SUDOKU-adit.git](https://github.com/yourusername/SUDOKU-adit.git)
    cd SUDOKU-adit
    ```

2.  **Import the project into Eclipse:**
    -   Open Eclipse IDE.
    -   Go to `File` -> `Import` -> `Existing Projects into Workspace`.
    -   Select the project directory.

3.  **Configure the database:**
    -   Create a MySQL database.
    -   Update the database connection details in the project.

4.  **Build and deploy the project:**
    -   Right-click the project in Eclipse.
    -   Select `Run As` -> `Run on Server`.

## Usage

1.  Open a web browser and navigate to `http://localhost:8080/SUDOKU-adit`.
2.  Register a new user or log in with existing credentials.
3.  Enter a Sudoku puzzle and click the solve button.

## Contributing

Feel free to submit issues, fork the repository, and send pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

---
*Note: Replace `Adi3220` with your actual GitHub username.*

