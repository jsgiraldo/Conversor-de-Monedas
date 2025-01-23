<p align="center">
</p>

# Currency Converter 💱🌐💸

Welcome to the Currency Converter project, developed as part of the Currency Converter Challenge by Alura Latam in collaboration with Oracle in the ONE program, specializing in Back-End development.

## Project Overview 📜

This Java-based Currency Converter allows you to convert various currencies using real-time exchange rates from an API. The application can make API requests, parse JSON responses, filter relevant currencies, and display the results clearly and concisely. Additionally, it maintains a conversion history with timestamps for each query, enabling users to track their previous conversions.

## Technologies Used 🛠️

- **Programming Language:** Java
- **Exchange Rate API:** Real-time exchange rate API for obtaining conversion rates.
- **Gson Library:** Used for parsing JSON responses from the API and converting them into Java objects.
- **Version Control:** Git/GitHub for version control and team collaboration.
- **IDE:** IntelliJ IDEA for development, debugging, and running the Java code.

## Classes and Features 🔍

### ConsultaConversion.java

Handles API queries to obtain exchange rates between different currencies.

### Calculations.java

Manages the logic for currency conversions, utilizing exchange rate information from `ConsultaConversion`.

### Principal.java

The main entry point of the program, managing user interaction through the console, displaying a menu of options, and handling currency conversions.

### GeneradorDeArchivos.java

Responsible for saving the query history to a text file.

## Crafted with 💡 by
- Jordan Giraldo

## Usage Instructions 🚀

1. **Clone the Repository:** Clone this repository to your local machine using the command:
   ```sh
   git clone https://github.com/jsgiraldo/Conversor-de-Monedas.git
  2. **Navigate to the Project Directory:** Change to the project directory:
    ```sh
    cd Conversor-de-Monedas
    ```

  3. **Compile the Java Files:** Compile the Java source files using the following command:
    ```sh
    javac -d bin src/*.java
    ```

  4. **Run the Application:** Execute the main class to start the currency converter:
    ```sh
    java -cp bin Principal
    ```

  5. **Follow the On-Screen Instructions:** Use the console menu to perform currency conversions and view the conversion history.

