# Thanos Project

## Project Overview
The **Thanos Project** is an educational project designed to explore file manipulation using Python. The goal is to demonstrate fundamental operations like copying, deleting, and renaming files in a folder-based environment. This project was developed using Jupyter Notebook for easy execution and visualization.

## Objective
The main objective of this project is to:
1. Learn how to manage and manipulate files and directories.
2. Perform random operations on a set of files, mimicking the famous "Thanos snap" by deleting half the files randomly.
3. Reinforce Python's capabilities in automation tasks such as file handling, random operations, and folder management.

## Features
1. **Backup Population**: A function to copy all files from the main folder (`universe`) to a backup folder.
2. **Random Deletion**: A function to randomly delete half of the files in the `universe` folder, simulating the "Thanos snap."
3. **Restore Population**: Ability to restore the population (files) from the backup folder.
4. **Randomized File Names**: An extra feature where the files are copied into a new folder with completely randomized names to explore random file handling.
   
## Libraries Used
- **os**: To interact with the file system and directories.
- **shutil**: For copying and managing files.
- **random**: For generating random names and performing random deletions.
- **string**: Used for generating random characters in file names.

## How to Run the Project
1. Clone the project repository to your local machine:
   ```bash
   git clone https://github.com/moha22021/thanos-project.git
