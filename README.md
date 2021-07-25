# 😎 Learn Python 😎

This is a great place to start learning Python. Full credit goes to Eric Matthes.



## Table of Contents
* 1 Getting Started

## 1 GETTING STARTED 
In this chapter, you’ll run your first Python program, hello_world.py. First, you’ll need to check whether a recent version of Python is installed on your computer; if it isn’t, you’ll install it. You’ll also install a text editor to work with your Python programs. Text editors recognize Python code and highlight sections as you write, making it easy to understand your code’s structure. 

### Setting Up Your Programming Environment
Python differs slightly on different operating systems, so you’ll need to keep a few considerations in mind. In the following sections, we’ll make sure Python is set up correctly on your system. 

#### Python Versions
Every programming language evolves as new ideas and technologies emerge, and the developers of Python have continually made the language more versatile and powerful. As of this writing, the latest version is Python 3.7, but everything in this book should run on Python 3.6 or later. In this section, we’ll find out if Python is already installed on your system and whether you need to install a newer version. Appendix A contains a comprehensive guide to installing the latest version of Python on each major operating system as well. Some old Python projects still use Python 2, but you should use Python 3. If Python 2 is installed on your system, it’s probably there to support some older programs that your system needs. We’ll leave this installation as is, and make sure you have a more recent version to work with. 

#### Running Snippets of Python Code
You can run Python’s interpreter in a terminal window, allowing you to try bits of Python code without having to save and run an entire program. Throughout this book, you’ll see code snippets that look like this: 

    ➊ >>> print("Hello Python interpreter!")
        Hello Python interpreter! 
   
The >>> prompt indicates that you should be using the terminal window, and the bold text is the code you should type in and then execute by pressing ENTER. Most of the examples in the book are small, self-contained programs that you’ll run from your text editor rather than the terminal, because you’ll write most of your code in the text editor. But sometimes basic concepts will be shown in a series of snippets run through a Python terminal session to demonstrate particular concepts more efficiently. When you see three angle brackets in a code listing ➊, you’re looking at code and output from a terminal session. We’ll try coding in the interpreter on your system in a moment. We’ll also use a text editor to create a simple program called Hello World! that has become a staple of learning to program. There’s a long-held tradition in the programming world that printing a Hello world! message to the screen as your first program in a new language will bring you good luck. Such a simple program serves a very real purpose. If it runs correctly on your system, any Python program you write should work as well.

#### About the Sublime Text Editor
Sublime Text is a simple text editor that can be installed on all modern operating systems. Sublime Text lets you run almost all of your programs directly from the editor instead of through a terminal. Your code runs in a terminal session embedded in the Sublime Text window, which makes it easy to see the output. Sublime Text is a beginner-friendly editor, but many professional programmers use it as well. If you become comfortable using it while learning Python, you can continue using it as you progress to larger and more complicated projects. Sublime Text has a very liberal licensing policy: you can use the editor free of charge as long as you want, but the developers request that you purchase a license if you like it and want to keep using it. Appendix B provides information on other text editors. If you’re curious about the other options, you might want to skim that appendix at this point. If you want to begin programming quickly, you can use Sublime Text to start and consider other editors once you’ve gained some experience as a programmer. In this chapter, I’ll walk you through installing Sublime Text on your operating system. 

### Python on Different Operating Systems
Python is a cross-platform programming language, which means it runs on all the major operating systems. Any Python program you write should run on any modern computer that has Python installed. However, the methods for setting up Python on different operating systems vary slightly. In this section, you’ll learn how to set up Python on your system. You’ll first check whether a recent version of Python is installed on your system and install it if it’s not. Then you’ll install Sublime Text. These are the only two steps that are different for each operating system. In the sections that follow, you’ll run the Hello World! program and troubleshoot anything that didn’t work. I’ll walk you through this process for each operating system, so you’ll have a beginner-friendly Python programming environment. 

#### Python on Windows 
Windows doesn’t always come with Python, so you’ll probably need to install it, and then install Sublime Text. 

##### Installing Python 
First, check whether Python is installed on your system. Open a command window by entering command into the Start menu or by holding down the SHIFT key while right-clicking on your desktop and selecting Open command window here from the menu. In the terminal window, enter python in lowercase. If you get a Python prompt (>>>) in response, Python is installed on your system. If you see an error message telling you that python is not a recognized command, Python isn’t installed. In that case, or if you see a version of Python earlier than Python 3.6, you need to download a Python installer for Windows. Go to https://python.org/ and hover over the Downloads link. You should see a button for downloading the latest version of Python. Click the button, which should automatically start downloading the correct installer for your system. After you’ve downloaded the file, run the installer. Make sure you select the option Add Python to PATH, which will make it easier to configure your system correctly. 

##### Running Python in a Terminal Session 
Open a command window and enter python in lowercase. You should see a Python prompt (>>>), which means Windows has found the version of Python you just installed. 

     C:\> python
     Python 3.7.2 (v3.7.2:9a3ffc0492, Dec 23 2018, 23:09:28) [MSC v.1916 64 bit
     (AMD64)] on win32
     Type "help", "copyright", "credits" or "license" for more information.
     >>> 

NOTE: If you don’t see this output or something similar, see the more detailed setup instructions in Appendix A. 

Enter the following line in your Python session, and make sure you see the output Hello Python interpreter! 
     
    >>> print("Hello Python interpreter!")
    Hello Python interpreter!
    >>> 
    
Any time you want to run a snippet of Python code, open a command window and start a Python terminal session. To close the terminal session, press CTRL-Z and then press ENTER, or enter the command exit(). 

##### Installing Sublime Text 
You can download an installer for Sublime Text at https://sublimetext.com/. Click the download link and look for a Windows installer. After downloading the installer, run the installer and accept all of its defaults. 

#### Python on macOS
Python is already installed on most macOS systems, but it’s most likely an outdated version that you won’t want to learn on. In this section, you’ll install the latest version of Python, and then you’ll install Sublime Text and make sure it’s configured correctly. 

##### Checking Whether Python 3 Is Installed
Open a terminal window by going to Applications ▸ Utilities ▸ Terminal. You can also press command-spacebar, type terminal, and then press ENTER. To see which version of Python is installed, enter python with a lowercase p—this also starts the Python interpreter within the terminal, allowing you to enter Python commands. You should see output telling you which Python version is installed on your system and a >>> prompt where you can start entering Python commands, like this: 

    $ python
    Python 2.7.15 (default, Aug 17 2018, 22:39:05)
    [GCC 4.2.1 Compatible Apple LLVM 9.1.0 (clang-902.0.39.2)] on darwin
    Type "help", "copyright", "credits", or "license" for more information.
    >>> 
    
This output indicates that Python 2.7.15 is currently the default version installed on this computer. Once you’ve seen this output, press CTRL-D or enter exit() to leave the Python prompt and return to a terminal prompt. To check whether you have Python 3 installed, enter the command python3. You’ll probably get an error message, meaning you don’t have any versions of Python 3 installed. If the output shows you have Python 3.6 or a later version installed, you can skip ahead to “Running Python in a Terminal Session”. If Python 3 isn’t installed by default, you’ll need to install it manually. Note that whenever you see the python command in this book, you need to use the python3 command instead to make sure you’re using Python 3, not Python 2; they differ significantly enough that you’ll run into trouble trying to run the code in this book using Python 2. If you see any version earlier than Python 3.6, follow the instructions in the next section to install the latest version. 

##### Installing the Latest Version of Python
You can find a Python installer for your system at https://python.org/. Hover over the Download link, and you should see a button for downloading the latest Python version. Click the button, which should automatically start downloading the correct installer for your system. After the file downloads, run the installer. When you’re finished, enter the following at a terminal prompt: 

    $ python3 --version
    Python 3.7.2 
    
You should see output similar to this, in which case, you’re ready to try out Python. Whenever you see the command python, make sure you use python3. 

##### Running Python in a Terminal Session 
You can now try running snippets of Python code by opening a terminal and typing python3. Enter the following line in the terminal session: 

    >>> print("Hello Python interpreter!")
    Hello Python interpreter!
    >>> 
    
Your message should print directly in the current terminal window. Remember that you can close the Python interpreter by pressing CTRL-D or by entering the command exit(). 

##### Installing Sublime Text 
To install the Sublime Text editor, you need to download the installer at https://sublimetext.com/. Click the Download link and look for an installer for macOS. After the installer downloads, open it and then drag the Sublime Text icon into your Applications folder. 

#### Python on Linux 
Linux systems are designed for programming, so Python is already installed on most Linux computers. The people who write and maintain Linux expect you to do your own programming at some point and encourage you to do so. For this reason, there’s very little to install and only a few settings to change to start programming. 

##### Checking Your Version of Python
Open a terminal window by running the Terminal application on your system (in Ubuntu, you can press CTRL-ALT-T). To find out which version of Python is installed, enter python3 with a lowercase p. When Python is installed, this command starts the Python interpreter. You should see output indicating which version of Python is installed and a >>> prompt where you can start entering Python commands, like this: 
    
    $ python3
    Python 3.7.2 (default, Dec 27 2018, 04:01:51)
    [GCC 7.3.0] on linux
    Type "help", "copyright", "credits" or "license" for more information.
    >>>
    
This output indicates that Python 3.7.2 is currently the default version of Python installed on this computer. When you’ve seen this output, press CTRL-D or enter exit() to leave the Python prompt and return to a terminal prompt. Whenever you see the python command in this book, enter python3 instead. You’ll need Python 3.6 or later to run the code in this book. If the Python version installed on your system is earlier than Python 3.6, refer to Appendix A to install the latest version. 

##### Running Python in a Terminal Session 
You can try running snippets of Python code by opening a terminal and entering python3, as you did when checking your version. Do this again, and when you have Python running, enter the following line in the terminal session: 

    >>> print("Hello Python interpreter!")
    Hello Python interpreter!
    >>> 
    
The message should print directly in the current terminal window. Remember that you can close the Python interpreter by pressing CTRL-D or by entering the command exit(). 

##### Installing Sublime Text 
On Linux, you can install Sublime Text from the Ubuntu Software Center. Click the Ubuntu Software icon in your menu, and search for Sublime Text. Click to install it, and then launch it. 

### Running a Hello World Program 
With a recent version of Python and Sublime Text installed, you’re almost ready to run your first Python program written in a text editor. But before doing so, you need to make sure Sublime Text is set up to use the correct version of Python on your system. Then you’ll write the Hello World! program and run it. 

#### Configuring Sublime Text to Use the Correct Python Version 
If the python command on your system runs Python 3, you won’t need to configure anything and can skip to the next section. If you use the python3 command, you’ll need to configure Sublime Text to use the correct Python version when it runs your programs. Click the Sublime Text icon to launch it, or search for Sublime Text in your system’s search bar and then launch it. Go to Tools ▸ Build System ▸ New Build System, which will open a new configuration file for you. Delete what you see and enter the following: 

    Python3.sublime-build 
    ------------------------------------------------------------------
    {
    "cmd": ["python3", "-u", "$file"],
    } 
    ------------------------------------------------------------------
    
This code tells Sublime Text to use your system’s python3 command when running your Python program files. Save the file as Python3.sublime-build in the default directory that Sublime Text opens when you choose Save. 

### Running hello_world.py 
Before you write your first program, make a folder called python_work somewhere on your system for your projects. It’s best to use lowercase letters and underscores for spaces in file and folder names, because Python uses these naming conventions. Open Sublime Text, and save an empty Python file (File ▸ Save As) called hello_world.py in your python_work folder. The extension .py tells Sublime Text that the code in your file is written in Python, which tells it how to run the program and highlight the text in a helpful way. After you’ve saved your file, enter the following line in the text editor: 

    hello_world.py 
    ------------------------------------------------------------------
    print("Hello Python world!") 
    ------------------------------------------------------------------
    
If the python command works on your system, you can run your program by selecting Tools ▸ Build in the menu or by pressing CTRL-B (Command-B on macOS). If you had to configure Sublime Text in the previous section, select Tools ▸ Build System and then select Python 3. From now on you’ll be able to select Tools ▸ Build or just press CTRL-B (or -B) to run your programs. A terminal screen should appear at the bottom of the Sublime Text window, showing the following output: 

    Hello Python world!
    [Finished in 0.1s] 
    
If you don’t see this output, something might have gone wrong in the program. Check every character on the line you entered. Did you accidentally capitalize print? Did you forget one or both of the quotation marks or parentheses? Programming languages expect very specific syntax, and if you don’t provide that, you’ll get errors. If you can’t get the program to run, see the suggestions in the next section. 

### Troubleshooting 
If you can’t get hello_world.py to run, here are a few remedies you can try that are also good general solutions for any programming problem: When a program contains a significant error, Python displays a traceback, which is an error report. Python looks through the file and tries to identify the problem. Check the traceback; it might give you a clue as to what issue is preventing the program from running. 
- Step away from your computer, take a short break, and then try again. Remember that syntax is very important in programming, so even a missing colon, a mismatched quotation mark, or mismatched parentheses can prevent a program from running properly. Reread the relevant parts of this chapter, look over your code, and try to find the mistake. 
- Start over again. You probably don’t need to uninstall any software, but it might make sense to delete your hello_world.py file and re-create it from scratch. 
- Ask someone else to follow the steps in this chapter, on your computer or a different one, and watch what they do carefully. You might have missed one small step that someone else happens to catch. 
- Find someone who knows Python and ask them to help you get set up. If you ask around, you might find that you unexpectedly know someone who uses Python. The setup instructions in this chapter are also available through the book’s companion website at [Nostarch.com](https://nostarch.com/pythoncrashcourse2e/). The online version of these instructions might work better for you because you can simply cut and paste code. 
- Ask for help online. Appendix C provides a number of resources, such as forums and live chat sites, where you can ask for solutions from people who’ve already worked through the issue you’re currently facing. 

Never worry that you’re bothering experienced programmers. Every programmer has been stuck at some point, and most programmers are happy to help you set up your system correctly. As long as you can state clearly what you’re trying to do, what you’ve already tried, and the results you’re getting, there’s a good chance someone will be able to help you. As mentioned in the Introduction, the Python community is very friendly and welcoming to beginners. Python should run well on any modern computer. Early setup issues can be frustrating, but they’re well worth sorting out. Once you get hello_world.py running, you can start to learn Python, and your programming work will become more interesting and satisfying. 

### Running Python Programs from a Terminal 
Most of the programs you write in your text editor you’ll run directly from the editor. But sometimes it’s useful to run programs from a terminal instead. For example, you might want to run an existing program without opening it for editing. You can do this on any system with Python installed if you know how to access the directory where the program file is stored. To try this, make sure you’ve saved the hello_world.py file in the python_work folder on your desktop. 

#### On Windows 
You can use the terminal command cd, for change directory, to navigate through your filesystem in a command window. The command dir, for directory, shows you all the files that exist in the current directory. Open a new terminal window and enter the following commands to run hello_world.py: 

    ➊ C:\> cd Desktop\python_work
    ➋ C:\Desktop\python_work> dir
       hello_world.py
    ➌ C:\Desktop\python_work> python hello_world.py
       Hello Python world! 
   
At ➊ you use the cd command to navigate to the python_work folder, which is in the Desktop folder. Next, you use the dir command to make sure hello_world.py is in this folder ➋. Then you run the file using the command python hello_world.py ➌. Most of your programs will run fine directly from your editor. But as your work becomes more complex, you’ll want to run some of your programs from a terminal. 

#### On macOS and Linux 
Running a Python program from a terminal session is the same on Linux and macOS. You can use the terminal command cd, for change directory, to navigate through your filesystem in a terminal session. The command ls, for list, shows you all the nonhidden files that exist in the current directory. Open a new terminal window and enter the following commands to run hello_world.py: 
    ➊ ~$ cd Desktop/python_work/
    ➋ ~/Desktop/python_work$ ls
       hello_world.py
    ➌ ~/Desktop/python_work$ python hello_world.py
       Hello Python world! 
   
At ➊ you use the cd command to navigate to the python_work folder, which is in the Desktop folder. Next, you use the ls command to make sure hello_world.py is in this folder ➋. Then you run the file using the command python hello_world.py ➌. It’s that simple. You just use the python (or python3) command to run Python programs. 

### TRY IT YOURSELF 
The exercises in this chapter are exploratory in nature. Starting in Chapter 2, the challenges you’ll solve will be based on what you’ve learned. 

1-1. python.org: Explore the Python home page (https://python.org/) to find topics that interest you. As you become familiar with Python, different parts of the site will be more useful to you. 

1-2. Hello World Typos: Open the hello_world.py file you just created. Make a typo somewhere in the line and run the program again. Can you make a typo that generates an error? Can you make sense of the error message? Can you make a typo that doesn’t generate an error? Why do you think it didn’t make an error? 

1-3. Infinite Skills: If you had infinite programming skills, what would you build? You’re about to learn how to program. If you have an end goal in mind, you’ll have an immediate use for your new skills; now is a great time to draft descriptions of what you want to create. It’s a good habit to keep an “ideas” notebook that you can refer to whenever you want to start a new project. Take a few minutes now to describe three programs you want to create. 

### Summary
In this chapter, you learned a bit about Python in general, and you installed Python on your system if it wasn’t already there. You also installed a text editor to make it easier to write Python code. You ran snippets of Python code in a terminal session, and you ran your first program, hello_world.py. You probably learned a bit about troubleshooting as well. In the next chapter, you’ll learn about the different kinds of data you can work with in your Python programs, and you’ll use variables as well.

## 2 VARIABLES AND SIMPLE DATA TYPES 
In this chapter you’ll learn about the different kinds of data you can work with in your Python programs. You’ll also learn how to use variables to represent data in your programs. 

### What Really Happens When You Run hello_world.py 
Let’s take a closer look at what Python does when you run hello_world.py. As it turns out, Python does a fair amount of work, even when it runs a simple program: 

    hello_world.py 
    ------------------------------------------------------------------
    print("Hello Python world!") 
    ------------------------------------------------------------------
    
When you run this code, you should see this output: 
    
    Hello Python world! 
    
When you run the file hello_world.py, the ending .py indicates that the file is a Python program. Your editor then runs the file through the Python interpreter, which reads through the program and determines what each word in the program means. For example, when the interpreter sees the word print followed by parentheses, it prints to the screen whatever is inside the parentheses. As you write your programs, your editor highlights different parts of your program in different ways. For example, it recognizes that print() is the name of a function and displays that word in one color. It recognizes that "Hello Python world!" is not Python code and displays that phrase in a different color. This feature is called syntax highlighting and is quite useful as you start to write your own programs. 

## Variables 
Let’s try using a variable in hello_world.py. Add a new line at the beginning of the file, and modify the second line: 

    hello_world.py 
    ------------------------------------------------------------------
    message = "Hello Python world!"
    print(message) 
    ------------------------------------------------------------------
    
Run this program to see what happens. You should see the same output you saw previously: 
    
    Hello Python world! 
    
We’ve added a variable named message. Every variable is connected to a value, which is the information associated with that variable. In this case the value is the "Hello Python world!" text. Adding a variable makes a little more work for the Python interpreter. When it processes the first line, it associates the variable message with the "Hello Python world!" text. When it reaches the second line, it prints the value associated with message to the screen. Let’s expand on this program by modifying hello_world.py to print a second message. Add a blank line to hello_world.py, and then add two new lines of code: 

    message = "Hello Python world!"
    print(message)
    message = "Hello Python Crash Course world!"
    print(message) 
    
Now when you run hello_world.py, you should see two lines of output: 

    Hello Python world!
    Hello Python Crash Course world! 
    
You can change the value of a variable in your program at any time, and Python will always keep track of its current value. 

#### Naming and Using Variables 
When you’re using variables in Python, you need to adhere to a few rules and guidelines. Breaking some of these rules will cause errors; other guidelines just help you write code that’s easier to read and understand. Be sure to keep the following variable rules in mind: 

- Variable names can contain only letters, numbers, and underscores. They can start with a letter or an underscore, but not with a number. For instance, you can call a variable message_1 but not 1_message. 
- Spaces are not allowed in variable names, but underscores can be used to separate words in variable names. For example, greeting_message works, but greeting message will cause errors. 
- Avoid using Python keywords and function names as variable names; that is, do not use words that Python has reserved for a particular programmatic purpose, such as the word print. (See “Python Keywords and Built-in Functions” on Appendix A.) 
- Variable names should be short but descriptive. For example, name is better than n, student_name is better than s_n, and name_length is better than length_of_persons_name. 
- Be careful when using the lowercase letter l and the uppercase letter O because they could be confused with the numbers 1 and 0. 

It can take some practice to learn how to create good variable names, especially as your programs become more interesting and complicated. As you write more programs and start to read through other people’s code, you’ll get better at coming up with meaningful names. 

NOTE: The Python variables you’re using at this point should be lowercase. You won’t get errors if you use uppercase letters, but uppercase letters in variable names have special meanings that we’ll discuss in later chapters. 

#### Avoiding Name Errors When Using Variables 
Every programmer makes mistakes, and most make mistakes every day. Although good programmers might create errors, they also know how to respond to those errors efficiently. Let’s look at an error you’re likely to make early on and learn how to fix it. We’ll write some code that generates an error on purpose. Enter the following code, including the misspelled word mesage shown in bold: 

    message = "Hello Python Crash Course reader!"
    print(mesage) 
    
When an error occurs in your program, the Python interpreter does its best to help you figure out where the problem is. The interpreter provides a traceback when a program cannot run successfully. A traceback is a record of where the interpreter ran into trouble when trying to execute your code. Here’s an example of the traceback that Python provides after you’ve accidentally misspelled a variable’s name: 

    Traceback (most recent call last):
    ➊    File "hello_world.py", line 2, in <module>
    ➋      print(mesage)
    ➌ NameError: name 'mesage' is not defined 
    
The output at ➊ reports that an error occurs in line 2 of the file hello_world.py. The interpreter shows this line ➋ to help us spot the error quickly and tells us what kind of error it found ➌. In this case it found a name error and reports that the variable being printed, mesage, has not been defined. Python can’t identify the variable name provided. A name error usually means we either forgot to set a variable’s value before using it, or we made a spelling mistake when entering the variable’s name. Of course, in this example we omitted the letter s in the variable name message in the second line. The Python interpreter doesn’t spellcheck your code, but it does ensure that variable names are spelled consistently. For example, watch what happens when we spell message incorrectly in another place in the code as well: 

    mesage = "Hello Python Crash Course reader!"
    print(mesage) 
    
In this case, the program runs successfully! Hello Python Crash Course reader! Programming languages are strict, but they disregard good and bad spelling. As a result, you don’t need to consider English spelling and grammar rules when you’re trying to create variable names and writing code. Many programming errors are simple, single-character typos in one line of a program. If you’re spending a long time searching for one of these errors, know that you’re in good company. Many experienced and talented programmers spend hours hunting down these kinds of tiny errors. Try to laugh about it and move on, knowing it will happen frequently throughout your programming life. 

#### Variables Are Labels 
Variables are often described as boxes you can store values in. This idea can be helpful the first few times you use a variable, but it isn’t an accurate way to describe how variables are represented internally in Python. It’s much better to think of variables as labels that you can assign to values. You can also say that a variable references a certain value. This distinction probably won’t matter much in your initial programs, but it’s worth learning earlier rather than later. At some point, you’ll see unexpected behavior from a variable, and an accurate understanding of how variables work will help you identify what’s happening in your code. 

NOTE: The best way to understand new programming concepts is to try using them in your programs. If you get stuck while working on an exercise in this book, try doing something else for a while. If you’re still stuck, review the relevant part of that chapter. If you still need help, see the suggestions in Appendix C. 

#### TRY IT YOURSELF 
Write a separate program to accomplish each of these exercises. Save each program with a filename that follows standard Python conventions, using lowercase letters and underscores, such as simple_message.py and simple_messages.py. 

2-1. Simple Message: Assign a message to a variable, and then print that message. 

2-2. Simple Messages: Assign a message to a variable, and print that message. Then change the value of the variable to a new message, and print the new message. 

### Strings 
Because most programs define and gather some sort of data, and then do something useful with it, it helps to classify different types of data. The first data type we’ll look at is the string. Strings are quite simple at first glance, but you can use them in many different ways. A string is a series of characters. Anything inside quotes is considered a string in Python, and you can use single or double quotes around your strings like this: 

    "This is a string."
    'This is also a string.' 
    
This flexibility allows you to use quotes and apostrophes within your strings: 

    'I told my friend, "Python is my favorite language!"'
    "The language 'Python' is named after Monty Python, not the snake."
    "One of Python's strengths is its diverse and supportive community." 
    
Let’s explore some of the ways you can use strings. 

#### Changing Case in a String with Methods 
One of the simplest tasks you can do with strings is change the case of the words in a string. Look at the following code, and try to determine what’s happening: 

    name.py 
    ------------------------------------------------------------------
    name = "ada lovelace"
    print(name.title()) 
    ------------------------------------------------------------------
    
Save this file as name.py, and then run it. You should see this output: 

    Ada Lovelace 
    
In this example, the variable name refers to the lowercase string "ada lovelace". The method title() appears after the variable in the print() call. A method is an action that Python can perform on a piece of data. The dot (.) after name in name.title() tells Python to make the title() method act on the variable name. Every method is followed by a set of parentheses, because methods often need additional information to do their work. That information is provided inside the parentheses. The title() function doesn’t need any additional information, so its parentheses are empty. The title() method changes each word to title case, where each word begins with a capital letter. This is useful because you’ll often want to think of a name as a piece of information. For example, you might want your program to recognize the input values Ada, ADA, and ada as the same name, and display all of them as Ada. Several other useful methods are available for dealing with case as well. For example, you can change a string to all uppercase or all lowercase letters like this: 

    name = "Ada Lovelace"
    print(name.upper())
    print(name.lower()) 
    
This will display the following: 

    ADA LOVELACE
    ada lovelace 
    
The lower() method is particularly useful for storing data. Many times you won’t want to trust the capitalization that your users provide, so you’ll convert strings to lowercase before storing them. Then when you want to display the information, you’ll use the case that makes the most sense for each string. 

#### Using Variables in Strings 
In some situations, you’ll want to use a variable’s value inside a string. For example, you might want two variables to represent a first name and a last name respectively, and then want to combine those values to display someone’s full name: 
    
    full_name.py 
    ------------------------------------------------------------------
    first_name = "ada"
    last_name = "lovelace"
    ➊ full_name = f"{first_name} {last_name}"
    print(full_name) 
    ------------------------------------------------------------------
    
To insert a variable’s value into a string, place the letter f immediately before the opening quotation mark ➊. Put braces around the name or names of any variable you want to use inside the string. Python will replace each variable with its value when the string is displayed. These strings are called f-strings. The f is for format, because Python formats the string by replacing the name of any variable in braces with its value. The output from the previous code is: 

    ada lovelace 
    
You can do a lot with f-strings. For example, you can use f-strings to compose complete messages using the information associated with a variable, as shown here: 

    first_name = "ada"
    last_name = "lovelace"
    full_name = f"{first_name} {last_name}"
    ➊ print(f"Hello, {full_name.title()}!") 
    
The full name is used in a sentence that greets the user ➊, and the title() method changes the name to title case. This code returns a simple but nicely formatted greeting: 

    Hello, Ada Lovelace! 
    
You can also use f-strings to compose a message, and then assign the entire message to a variable: 

    first_name = "ada"
    last_name = "lovelace"
    full_name = f"{first_name} {last_name}"
    ➊ message = f"Hello, {full_name.title()}!"
    ➋ print(message) 
    
This code displays the message Hello, Ada Lovelace! as well, but by assigning the message to a variable ➊ we make the final print() call much simpler ➋. 

NOTE: F-strings were first introduced in Python 3.6. If you’re using Python 3.5 or earlier, you’ll need to use the format() method rather than this f syntax. To use format(), list the variables you want to use in the string inside the parentheses following format. Each variable is referred to by a set of braces; the braces will be filled by the values listed in parentheses in the order provided: 

    full_name = "{} {}".format(first_name, last_name) 
    
#### Adding Whitespace to Strings with Tabs or Newlines 
In programming, whitespace refers to any nonprinting character, such as spaces, tabs, and end-of-line symbols. You can use whitespace to organize your output so it’s easier for users to read. To add a tab to your text, use the character combination \t as shown at ➊: 
   
    >>> print("Python")
       Python
    ➊ >>> print("\tPython")
       Python 
       
To add a newline in a string, use the character combination \n: 
    
    >>> print("Languages:\nPython\nC\nJavaScript")
    Languages:
    Python
    C
    JavaScript 
    
You can also combine tabs and newlines in a single string. The string "\n\t" tells Python to move to a new line, and start the next line with a tab. The following example shows how you can use a one-line string to generate four lines of output: 

    >>> print("Languages:\n\tPython\n\tC\n\tJavaScript")
    Languages:
        Python
        C
        JavaScript 
        
Newlines and tabs will be very useful in the next two chapters when you start to produce many lines of output from just a few lines of code. 

#### Stripping Whitespace 
Extra whitespace can be confusing in your programs. To programmers 'python' and 'python ' look pretty much the same. But to a program, they are two different strings. Python detects the extra space in 'python ' and considers it significant unless you tell it otherwise. It’s important to think about whitespace, because often you’ll want to compare two strings to determine whether they are the same. For example, one important instance might involve checking people’s usernames when they log in to a website. Extra whitespace can be confusing in much simpler situations as well. Fortunately, Python makes it easy to eliminate extraneous whitespace from data that people enter. Python can look for extra whitespace on the right and left sides of a string. To ensure that no whitespace exists at the right end of a string, use the rstrip() method. 

    ➊ >>> favorite_language = 'python '
    ➋ >>> favorite_language
       'python '
    ➌ >>> favorite_language.rstrip()
       'python'
    ➍ >>> favorite_language
       'python ' 
       
The value associated with favorite_language at ➊ contains extra whitespace at the end of the string. When you ask Python for this value in a terminal session, you can see the space at the end of the value ➋. When the rstrip() method acts on the variable favorite_language at ➌, this extra space is removed. However, it is only removed temporarily. If you ask for the value of favorite_language again, you can see that the string looks the same as when it was entered, including the extra whitespace ➍. To remove the whitespace from the string permanently, you have to associate the stripped value with the variable name: 
    
    >>> favorite_language = 'python '
    ➊ >>> favorite_language = favorite_language.rstrip()
    >>> favorite_language
       'python' 

To remove the whitespace from the string, you strip the whitespace from the right side of the string and then associate this new value with the original variable, as shown at ➊. Changing a variable’s value is done often in programming. This is how a variable’s value can be updated as a program is executed or in response to user input. You can also strip whitespace from the left side of a string using the lstrip() method, or from both sides at once using strip(): 
    
    ➊ >>> favorite_language = ' python '
    ➋ >>> favorite_language.rstrip()
       ' python'
    ➌ >>> favorite_language.lstrip()
       'python '
    ➍ >>> favorite_language.strip()
       'python' 
       
In this example, we start with a value that has whitespace at the beginning and the end ➊. We then remove the extra space from the right side at ➋, from the left side at ➌, and from both sides at ➍. Experimenting with these stripping functions can help you become familiar with manipulating strings. In the real world, these stripping functions are used most often to clean up user input before it’s stored in a program. 

#### Avoiding Syntax Errors with Strings 
One kind of error that you might see with some regularity is a syntax error. A syntax error occurs when Python doesn’t recognize a section of your program as valid Python code. For example, if you use an apostrophe within single quotes, you’ll produce an error. This happens because Python interprets everything between the first single quote and the apostrophe as a string. It then tries to interpret the rest of the text as Python code, which causes errors. Here’s how to use single and double quotes correctly. Save this program as apostrophe.py and then run it: 

    apostrophe.py 
    ------------------------------------------------------------------
    message = "One of Python's strengths is its diverse community."
    ------------------------------------------------------------------
    print(message) 
    
The apostrophe appears inside a set of double quotes, so the Python interpreter has no trouble reading the string correctly: 

    One of Python's strengths is its diverse community. 
    
However, if you use single quotes, Python can’t identify where the string should end: message = 'One of Python's strengths is its diverse community.'
print(message) You’ll see the following output: 

    File "apostrophe.py", line 1
       message = 'One of Python's strengths is its diverse community.'
                               ^➊
    SyntaxError: invalid syntax
    
In the output you can see that the error occurs at ➊ right after the second single quote. This syntax error indicates that the interpreter doesn’t recognize something in the code as valid Python code. Errors can come from a variety of sources, and I’ll point out some common ones as they arise. You might see syntax errors often as you learn to write proper Python code. Syntax errors are also the least specific kind of error, so they can be difficult and frustrating to identify and correct. If you get stuck on a particularly stubborn error, see the suggestions in Appendix C. 

NOTE: Your editor’s syntax highlighting feature should help you spot some syntax errors quickly as you write your programs. If you see Python code highlighted as if it’s English or English highlighted as if it’s Python code, you probably have a mismatched quotation mark somewhere in your file. 

#### TRY IT YOURSELF 
Save each of the following exercises as a separate file with a name like name_cases.py. If you get stuck, take a break or see the suggestions in Appendix C. 

2-3. Personal Message: Use a variable to represent a person’s name, and print a message to that person. Your message should be simple, such as, “Hello Eric, would you like to learn some Python today?” 

2-4. Name Cases: Use a variable to represent a person’s name, and then print that person’s name in lowercase, uppercase, and title case. 

2-5. Famous Quote: Find a quote from a famous person you admire. Print the quote and the name of its author. Your output should look something like the following, including the quotation marks: Albert Einstein once said, “A person who never made a mistake never tried anything new.” 

2-6. Famous Quote 2: Repeat Exercise 2-5, but this time, represent the famous person’s name using a variable called famous_person. Then compose your message and represent it with a new variable called message. Print your message. 

2-7. Stripping Names: Use a variable to represent a person’s name, and include some whitespace characters at the beginning and end of the name. Make sure you use each character combination, "\t" and "\n", at least once. Print the name once, so the whitespace around the name is displayed. Then print the name using each of the three stripping functions, lstrip(), rstrip(), and strip(). 

### Numbers 
Numbers are used quite often in programming to keep score in games, represent data in visualizations, store information in web applications, and so on. Python treats numbers in several different ways, depending on how they’re being used. Let’s first look at how Python manages integers, because they’re the simplest to work with. 

#### Integers 
You can add (+), subtract (-), multiply (*), and divide (/) integers in Python. 

    >>> 2 + 3
    5
    >>> 3 - 2
    1
    >>> 2 * 3
    6
    >>> 3 / 2
    1.5 

In a terminal session, Python simply returns the result of the operation. Python uses two multiplication symbols to represent exponents: 

    >>> 3 ** 2
    9
    >>> 3 ** 3
    27
    >>> 10 ** 6
    1000000 
    
Python supports the order of operations too, so you can use multiple operations in one expression. You can also use parentheses to modify the order of operations so Python can evaluate your expression in the order you specify. For example: 

    >>> 2 + 3 * 4
    14
    >>> (2 + 3) * 4
    20 

The spacing in these examples has no effect on how Python evaluates the expressions; it simply helps you more quickly spot the operations that have priority when you’re reading through the code. 

#### Floats 
Python calls any number with a decimal point a float. This term is used in most programming languages, and it refers to the fact that a decimal point can appear at any position in a number. Every programming language must be carefully designed to properly manage decimal numbers so numbers behave appropriately no matter where the decimal point appears. For the most part, you can use decimals without worrying about how they behave. Simply enter the numbers you want to use, and Python will most likely do what you expect: 

    >>> 0.1 + 0.1
    0.2
    >>> 0.2 + 0.2
    0.4
    >>> 2 * 0.1
    0.2
    >>> 2 * 0.2
    0.4 

But be aware that you can sometimes get an arbitrary number of decimal places in your answer: 

    >>> 0.2 + 0.1
    2.30000000000000004
    >>> 3 * 0.1
    3.30000000000000004 

This happens in all languages and is of little concern. Python tries to find a way to represent the result as precisely as possible, which is sometimes difficult given how computers have to represent numbers internally. Just ignore the extra decimal places for now; you’ll learn ways to deal with the extra places when you need to in the projects in Part II. 

#### Integers and Floats
When you divide any two numbers, even if they are integers that result in a whole number, you’ll always get a float: 

    >>> 4/2
    6.0 

If you mix an integer and a float in any other operation, you’ll get a float as well: 

    >>> 1 + 2.0
    3.0
    >>> 2 * 3.0
    10.0
    >>> 3.0 ** 2
    11.0 

Python defaults to a float in any operation that uses a float, even if the output is a whole number. 

Underscores in Numbers 
When you’re writing long numbers, you can group digits using underscores to make large numbers more readable: 

    >>> universe_age = 14_000_000_000 

When you print a number that was defined using underscores, Python prints only the digits: 
    
    >>> print(universe_age)
    14000000000 

Python ignores the underscores when storing these kinds of values. Even if you don’t group the digits in threes, the value will still be unaffected. To Python, 1000 is the same as 1_000, which is the same as 10_00. This feature works for integers and floats, but it’s only available in Python 3.6 and later. 

#### Multiple Assignment 
You can assign values to more than one variable using just a single line. This can help shorten your programs and make them easier to read; you’ll use this technique most often when initializing a set of numbers. For example, here’s how you can initialize the variables x, y, and z to zero: 

    >>> x, y, z = 0, 0, 0 
    
You need to separate the variable names with commas, and do the same with the values, and Python will assign each value to its respectively positioned variable. As long as the number of values matches the number of variables, Python will match them up correctly. 

#### Constants 
A constant is like a variable whose value stays the same throughout the life of a program. Python doesn’t have built-in constant types, but Python programmers use all capital letters to indicate a variable should be treated as a constant and never be changed: 

    MAX_CONNECTIONS = 5000 
    
When you want to treat a variable as a constant in your code, make the name of the variable all capital letters. 

#### TRY IT YOURSELF 
2-8. Number Eight: Write addition, subtraction, multiplication, and division operations that each result in the number 8. Be sure to enclose your operations in print() calls to see the results. You should create four lines that look like this: 

    print(5+3) 
    
Your output should simply be four lines with the number 8 appearing once on each line. 
2-9. Favorite Number: Use a variable to represent your favorite number. Then, using that variable, create a message that reveals your favorite number. Print that message. 

### Comments 
Comments are an extremely useful feature in most programming languages. Everything you’ve written in your programs so far is Python code. As your programs become longer and more complicated, you should add notes within your programs that describe your overall approach to the problem you’re solving. A comment allows you to write notes in English within your programs. 

#### How Do You Write Comments? 
In Python, the hash mark (#) indicates a comment. Anything following a hash mark in your code is ignored by the Python interpreter. For example: 
    
    comment.py 
    ------------------------------------------------------------------
    # Say hello to everyone.
    print("Hello Python people!") 
    
Python ignores the first line and executes the second line. 

    Hello Python people! 
    
#### What Kind of Comments Should You Write? 
The main reason to write comments is to explain what your code is supposed to do and how you are making it work. When you’re in the middle of working on a project, you understand how all of the pieces fit together. But when you return to a project after some time away, you’ll likely have forgotten some of the details. You can always study your code for a while and figure out how segments were supposed to work, but writing good comments can save you time by summarizing your overall approach in clear English. If you want to become a professional programmer or collaborate with other programmers, you should write meaningful comments. Today, most software is written collaboratively, whether by a group of employees at one company or a group of people working together on an open source project. Skilled programmers expect to see comments in code, so it’s best to start adding descriptive comments to your programs now. Writing clear, concise comments in your code is one of the most beneficial habits you can form as a new programmer. When you’re determining whether to write a comment, ask yourself if you had to consider several approaches before coming up with a reasonable way to make something work; if so, write a comment about your solution. It’s much easier to delete extra comments later on than it is to go back and write comments for a sparsely commented program. From now on, I’ll use comments in examples throughout this book to help explain sections of code. 

#### TRY IT YOURSELF 
2-10. Adding Comments: Choose two of the programs you’ve written, and add at least one comment to each. If you don’t have anything specific to write because your programs are too simple at this point, just add your name and the current date at the top of each program file. Then write one sentence describing what the program does. 

### The Zen of Python 
Experienced Python programmers will encourage you to avoid complexity and aim for simplicity whenever possible. The Python community’s philosophy is contained in “The Zen of Python” by Tim Peters. You can access this brief set of principles for writing good Python code by entering import this into your interpreter. I won’t reproduce the entire “Zen of Python” here, but I’ll share a few lines to help you understand why they should be important to you as a beginning Python programmer. 
    
    >>> import this
    The Zen of Python, by Tim Peters
    Beautiful is better than ugly. 
    
Python programmers embrace the notion that code can be beautiful and elegant. In programming, people solve problems. Programmers have always respected well-designed, efficient, and even beautiful solutions to problems. As you learn more about Python and use it to write more code, someone might look over your shoulder one day and say, “Wow, that’s some beautiful code!” 

    Simple is better than complex. 
    
If you have a choice between a simple and a complex solution, and both work, use the simple solution. Your code will be easier to maintain, and it will be easier for you and others to build on that code later on. 

    Complex is better than complicated. 
    
Real life is messy, and sometimes a simple solution to a problem is unattainable. In that case, use the simplest solution that works. 

    Readability counts. 
    
Even when your code is complex, aim to make it readable. When you’re working on a project that involves complex coding, focus on writing informative comments for that code. 

    There should be one-- and preferably only one --obvious way to do it. 
    
If two Python programmers are asked to solve the same problem, they should come up with fairly compatible solutions. This is not to say there’s no room for creativity in programming. On the contrary! But much of programming consists of using small, common approaches to simple situations within a larger, more creative project. The nuts and bolts of your programs should make sense to other Python programmers. Now is better than never. You could spend the rest of your life learning all the intricacies of Python and of programming in general, but then you’d never complete any projects. Don’t try to write perfect code; write code that works, and then decide whether to improve your code for that project or move on to something new. As you continue to the next chapter and start digging into more involved topics, try to keep this philosophy of simplicity and clarity in mind. Experienced programmers will respect your code more and will be happy to give you feedback and collaborate with you on interesting projects. 

#### TRY IT YOURSELF 
2-11. Zen of Python: Enter import this into a Python terminal session and skim through the additional principles. 

### Summary 
In this chapter you learned to work with variables. You learned to use descriptive variable names and how to resolve name errors and syntax errors when they arise. You learned what strings are and how to display strings using lowercase, uppercase, and title case. You started using whitespace to organize output neatly, and you learned to strip unneeded whitespace from different parts of a string. You started working with integers and floats, and learned some of the ways you can work with numerical data. You also learned to write explanatory comments to make your code easier for you and others to read. Finally, you read about the philosophy of keeping your code as simple as possible, whenever possible. In Chapter 3 you’ll learn to store collections of information in data structures called lists. You’ll learn to work through a list, manipulating any information in that list.
