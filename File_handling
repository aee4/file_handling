# importing 'os' module enables checking if a file exists and deleting a file 
import os

def open_file(file_name, mode):
    try:
        # Use the 'open' function to open the file
        # there a several modes but the most common ones are:
        # 'r' for reading, 'w' for writing, 'a' for appending and 'r+' for both reading and writing 

        file = open(file_name, mode) 
        return file
    
    except FileNotFoundError:
        print(f"File '{file_name}' not found.")
        return None
    

# Define a function to close a file
def close_file(file):
    try:
        # Use the 'close' method to close the file
        # with "with open()" there's no need to close the file as it closes automatically

        file.close()

    except Exception as u:
        print(f"An error occurred: {u}")

# Define a function to read from a file
def read_from_file(file):
    try:
        # Use the 'read' method to read from the file
        file_content = file.read()

        # Return the content
        return file_content
    
    except Exception as u:
        print(f"An error occurred: {u}")
        return None

# Define a function to write to a file
def write_to_file(file, detail):
    try:
        # Use the 'write' method to write to the file
        file.write(detail)

    except Exception as u:
        print(f"An error occurred: {u}")

# Define a function to read a file line by line
def read_file_line_by_line(file):
    try:
        # Use a loop to read the file line by line
        for line in file:
            # Print each line
            print(line.strip())

    except Exception as u:
        print(f"An error occurred: {u}")

