# Python - Beginners

1. Running Python in a Terminal Session in Windows Operating System:
- Start --> Open Command Prompt
- Type 'python' to check if Python has been installed in the system and to initialize the Python session on your terminal
- Check if the following code returns any output :
  
        >>> print("Hello World!")
            Hello World!
- Now, to run the Python file, navigate to the folder directory using the commands -'cd' and 'dir'
- once the root directory path has been set, type  the following command to run the Python file -

        C:\dir_path\> python hello_world.py
                      Hello World!

2. Running a Python file in a Python terminal using VS Code Editor:
   
        >>> python folder_path/python_filename.py

### a. Variables in Python:

Storing the message in a variable and then printing the message, will give the output as follows -
  
        >>> message = "Hello World!"
        >>> print(message)

            Hello World!
 Here, 'message' is a variable. "Hello World!" is the value. 
 Now, try running the python file after updating the variable - 
 
        >>> message = "Hello World, I am Nikita!!"
        >>> print(message)

            Hello World, I am Nikita!

   ### b. Strings in Python:

  A String is a series of characters. Anything written inside a pair of single or double quotes is considered a string in Python. Some of the examples are mentioned below - 
  -  "I love New York City."
  - 'I am going to watch a movie this weekend.'
  - "My friend has a pet named 'Simba', who loves to play with his Frisbee!"

    ### # Methods:
    
    A method is an action that Python can perform on a piece of data.

    - .title(): the title() method helps to change each word to a title case where each word begins with a capital letter.
    - .upper(): the upper() method will change the string case to uppercase.
    - .lower(): the upper() method will change the string case to lowercase.
   
    ### # f-strings:

    - The f stands for format as  Python formats the string by replacing the name of any variables in braces with its value.
    - To insert a variable's value into a string, place the letter f immediately before the opening quotation mark, and put braces around the name or names of any variable you want to use inside a string. Python will replace each variable with its value when a string is displayed.

          >>> first_name = "nikita"
          >>> last_name = "gaurihar"
          >>> full_name = f"{first_name} {last_name}"
          >>> message = f"Hello, {full_name.title()}!"
          >>> print(message)

              Hello, Nikita Gaurihar!
    ### # Dealing with whitespace, tabs, and newlines :

      Whitespaces refers to any nonprinting characters such as spaces, tabs and end-of-line symbols.

     - To add a tab to your text, use '\t' :

           >>> print("Heyy, Would you like to join us for the Dinner ?")
           >>> print("Heyy, Would you like \t\tto join us for the Dinner ?")
           >>> print("\tHeyy,Would you like to join us for the Dinner ?")

               Heyy, Would you like to join us for the Dinner ?
               Heyy, Would you like            to join us for the Dinner ?
                       Heyy,Would you like to join us for the Dinner ?
       
     - To add a newline to a string, use '\n' :

           >>> print("Languages:\n\tPython\n\tC\n\tJava")

           Languages:
                    Python
                    C
                    Java
    - Stripping whitespaces - rstrip() and lstrip() :

          >>> hometown = '            Maharashtra                           '
          >>> print(hometown)
          >>> print(hometown.rstrip())
          >>> print(hometown.lstrip())
          >>> print(hometown.strip()) 

                        Maharashtra
                        Maharashtra
            Maharashtra
            Maharashtra
   
    ### # Removing Prefixes:

    .removeprefix() is the method used to remove the mentioned value within the braces as a prefix. This can be explained using the following code snippet - 
       
        >>> neu_url = 'https://www.northeastern.edu/'
        >>> x = neu_url.remove('https://')
        >>> print(x)

          www.northeastern.edu/
 
