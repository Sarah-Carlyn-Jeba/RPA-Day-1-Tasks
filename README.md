🤖 #RPA – Day 1 Tasks (UiPath Studio)

📌 Overview

This repository contains four basic UiPath Studio automation workflows designed to demonstrate fundamental RPA concepts such as variable handling, data types, workflow arguments, and string manipulation.

Each process is implemented as an individual workflow to ensure modularity and clarity.

🧠 Objectives

    Understand variables and data types

    Learn string operations and concatenation

    Implement workflow arguments

    Practice dynamic variable manipulation

    Use output mechanisms (Message Box / Output Panel)

⚙️ Processes Description

1️⃣ Full Name Generator

Description:

Generates a full name by combining first name and last name.

Implementation Details:

Variables: FirstName (String), LastName (String), FullName (String)

Logic:

FullName = FirstName + " " + LastName

Output displayed using Message Box

2️⃣ Pass a Name to Another Workflow

Description:

Demonstrates inter-workflow communication using arguments.

Implementation Details:

Main workflow passes a string variable ("UiPath")

Sub-workflow uses an In Argument: InputName (String)

Output:

"Welcome, " + InputName

Displayed via Message Box

3️⃣ Integer to String Conversion and Concatenation

Description:

Converts an integer to string and concatenates it with text.

Implementation Details:

Variables: Number (Int32), Result (String)

Logic:

Result = "The number is: " + Number.ToString

Output displayed using Message Box / Output Panel

4️⃣ Modify Variables Dynamically

Description:

Demonstrates runtime modification of variables and logging output.

Implementation Details:

Variables updated during execution

Output displayed using Write Line / Log Message

Shows how variable values evolve during execution

🛠️ Technologies Used

UiPath Studio

UiPath.System.Activities

▶️ How to Run

Open the project in UiPath Studio

Run individual .xaml files or Main.xaml

Observe outputs via:

Message Box

Output Panel

📊 Key Concepts Covered

Variable declaration and initialization

Data type conversion (Int32 → String)

String concatenation

Arguments (In direction)

Workflow modularization

Debugging using Output Panel

⚠️ Notes

Ensure all variables are properly initialized before use

Check argument mapping when invoking workflows

Use meaningful variable names for clarity

👩‍💻 Author

Sarah Carlyn Jeba.S
