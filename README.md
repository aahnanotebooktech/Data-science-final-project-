# Data-science-final-project-
The final project for data science from ibm
# Data Science Final Project Notebook

# List of Data Science Languages
languages = ["Python", "R", "SQL", "Julia", "Scala"]

# Display the languages in a formatted way
for language in languages:
    print(language)

# Commonly Used Data Science Libraries
libraries = ["Pandas", "NumPy", "Matplotlib", "Seaborn", "Scikit-learn", "TensorFlow"]

# Display the libraries in a formatted way
for library in libraries:
    print(library)

# Data Science Tools
data_science_tools = {
    "Tool Name": [
        "Jupyter Notebook",
        "RStudio",
        "Apache Hadoop",
        "TensorFlow",
        "RapidMiner",
    ],
    "Description": [
        "Interactive coding notebook",
        "IDE for R",
        "Big Data processing framework",
        "Deep Learning library",
        "Data Science platform",
    ],
}

# Display the data science tools in a formatted way
print("| Tool Name       | Description                     |")
print("|----------------|---------------------------------|")
for name, description in zip(data_science_tools["Tool Name"], data_science_tools["Description"]):
    print(f"| {name:<15} | {description:<35} |")

# Addition of two numbers
a = 3
b = 5
result = a + b
print("The sum of 3 and 5 is:", result)

# Convert minutes to hours
minutes = 150
hours = minutes / 60
print(f"{minutes} minutes is equal to {hours} hours")

## Objectives
# - List data science languages
# - List commonly used libraries and tools
# - Demonstrate arithmetic operations
# - Convert time units using code

## Author
# Name: Aahna Pathak
