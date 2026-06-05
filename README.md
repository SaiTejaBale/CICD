# Java Calculator

This project is a simple calculator application built using Java. It provides basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Project Structure

```
java-calculator
├── src
│   ├── main
│   │   └── java
│   │       └── com
│   │           └── calculator
│   │               ├── Calculator.java
│   │               ├── Operations.java
│   │               └── Main.java
│   └── test
│       └── java
│           └── com
│               └── calculator
│                   └── CalculatorTest.java
├── pom.xml
└── README.md
```

## Requirements

- Java Development Kit (JDK) 8 or higher
- Maven 3.6 or higher

## Building the Project

To build the project, navigate to the project directory and run the following command:

```
mvn clean install
```

## Running the Application

After building the project, you can run the calculator application using the following command:

```
mvn exec:java -Dexec.mainClass="com.calculator.Main"
```

## Testing

To run the unit tests for the Calculator class, use the following command:

```
mvn test
```

## Features

- Addition
- Subtraction
- Multiplication
- Division

## License

This project is licensed under the MIT License. See the LICENSE file for more details.