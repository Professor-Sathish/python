![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/Word%20Art%20Unit%205.png?raw=true)
# UNIT - 5 FILES, MODULES, PACKAGES 

### OBJECTIVE
Files and exception: text files, reading and writing files, format operator; command line arguments, errors and exceptions, handling exceptions, modules, packages; Illustrative programs: word count, copy file.

[Illustrative Problem Solutions](https://github.com/Professor-Sathish/GE_8151-unit-programs/tree/master/MD%20FILES)

[Memcode flashcards](https://www.memcode.com/courses/2280)	- 40+ flashcards to review the contents of this unit. Space repetition of the flashcards will help in retaining the content and perform better in exams."

[Kahoot for working with text files ](https://create.kahoot.it/share/unit-5-python-working-with-text-files/f6455c78-d279-4ed8-a10c-d04cb4df0b24)- Working with text files Quiz

[Kahoot for reading and writing files](https://create.kahoot.it/share/unit-5-reading-and-writing-to-python-files/f56821b1-79ff-49b6-b7fd-2d8116f6b7bf)- Reading and writing files Quiz

[Kahoot for Errors](https://create.kahoot.it/share/unit-5-errors/b964a59e-274c-4723-9a46-67c671f866c7) - Errors Quiz

[Kahoot for Exception ](https://create.kahoot.it/share/unit-5-exception/5cc77531-c67e-4485-a6e1-0a8f12fbfdc7) - Exception Quiz

[Kahoot for Modules](https://create.kahoot.it/share/unit-5-modules-in-python/639e31c4-0b09-4d03-a0aa-4cacaf252bed) - Modules Quiz

 #  TABLE OF CONTENTS
 
 [5.1.FILES](#51files)
 
 [5.1.1 What are files?](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#511-what-are-files)
 
 [5.1.2 File Extensions](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#512-file-extensions)
 
 [5.1.3 Types of Files](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#513-types-of-files)
 
[5.1.4 Common extensions that are binary file formats](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#514-common-extensions-that-are-binary-file-formats)

[5.1.5 Common extensions that are text file formats](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#515-common-extensions-that-are-text-file-formats)
 
 [5.2.TEXT FILE CHARACTERISTICS](#52text-file-characteristics)
 
[5.2.1 BINARY FILE CHARACTERISTICS](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#521-binary-file-characteristics)

[5.2.2 BASIC FILE OPERATIONS](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#522-basic-file-operations)
 
[5.3.READING TEXT FILES](#53reading-text-files)

 [5.3.1 DEMO  CODE](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#531-demo--code)
 
 [Reading text files with size parameter](#Reading-text-files-with-size-parameter)
 
[5.3.2 DEMO CODE](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#532-demo-code)

[Reading text files (Single Line)](#reading-text-files-Single-Line)

[5.3.3 DEMO CODE](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#533-demo-code)

[Reading text files (List of Lines)](#Reading-text-files-List-of-Lines)

  [5.3.4 DEMO CODE](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#534-demo-code)

 [5.4.WRITING TEXT FILES](#54WRITING-TEXT-FILES)
 
[5.4.1 Types of File Modes](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#541-types-of-file-modes)

 [5.4.2 Seek in File](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#542-seek-in-file)
 
 [5.4.3 DEMO CODE](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#543-demo-code)
 
 [5.5.FORMAT OPERATOR](#55FORMAT-OPERATOR)
 
 [5.6.COMMAND LINE ARGUMENTS](#56COMMAND-LINE-ARGUMENTS)
 
 [5.7.ERRORS AND EXCEPTIONS](#57ERRORS-AND-EXCEPTIONS)
 
 [5.8.HANDLING PYTHON LOGICAL ERRORS (EXCEPTIONS)](#58HANDLING-PYTHON-LOGICAL-ERRORS-(EXCEPTIONS))
 
 [5.8.1 BUILD IN EXCEPTIONS](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#581-build-in-exceptions)

 [5.9.MODULES](https://github.com/SubasriNatarajan/python/blob/main/Unit-5%20Files,Modules,Packages.md#59-modules)
 
 - [Illustrative Problems (Copy File)](#Illustrative-Problems-Copy-File)
 
 - [Illustrative Problems (Word Count)](#Illustrative-Problems-Word-Count)
 
### KEY TERMS
### File 
- A file is a container in a computer system for storing information. Files used in computers are similar in features to that of paper documents used in library and office files. In a computer operating system, files can be stored on optical drives, hard drives or other types of storage devices.
### Binary file 
- Binary file is a collection of bytes or a character stream. The data that is written into and read from binary file remain unchanged,+ with no separation between lines and no use of end-of-line characters and the interpretation of the files are left to the programmer.
### Text file 
- A text file is a stream of characters that can be processed sequentially and logically in the forward direction. The maximum number of characters in each line is limited to 255 characters.
### Sequential file access 
- In case of sequential file access, data is read from or written to a file in a sequential manner while the position indicator automatically gets adjusted by the stream I/O functions.
### Random file access 
- Random access means reading from or writing to any position in a file without reading or writing all the preceding data by controlling the position indicator
### Record 
- A record consists of a collection of data fields that conforms to a previously defined structure that can be stored on or retrieved from a file.
### Stream 
- The stream is a common, logical interface to the various devices that comprise the computer and is a logical interface to a file. Although files differ in form and capabilities, all streams are the same.
### File management 
- It basically means all operations related to creating, renaming, deleting, merging, reading, writing, etc. of any type of files.
### Path
- The path specifies the drive and/or directory (or folder) where the file is located. On PCs, the backslash character is used to separate directory names in a path. Some systems like Unix use the forward slash (/) as the directory separator.
# 5.1.FILES
### 5.1.1 What are files? 
*A file is sequential stream of bytes ending with an end-of-file marker. As we know, at the time of execution, every program is executed in the main memory. Main memory is volatile and the data would be lost once the program is terminated. If we need the same data again, we have to store the data in a file on the disk. A file is sequential stream of bytes ending with an end-of-file marker*
- Storage of data in variables and arrays is temporary—such data is lost when a program terminates. Files are used for permanent retention of data. Computers store files on secondary storage devices, such as hard drives, CDs, DVDs and flash drives. In this chapter, we explain how data files are created, updated and processed by C programs. We consider both sequential-access and random-access file processing.
### 5.1.2 File Extensions
- File extensions we can usually tell if a file is binary or text based on its file extension. This is because by convention the extension reflects the file format, but ultimately it is the file format that dictates whether the file data is binary or text.
### 5.1.3 Types of Files
- Text files
- Data files
- Directory files
- Binary files
- Graphic files
### 5.1.4 Common extensions that are binary file formats:
> Images: jpg, png, gif, bmp, tiff, psd, ...

> Videos: mp4, mkv, avi, mov, mpg, vob, ...

> Audio: mp3, aac, wav, flac, ogg, mka, wma, ...

> Documents: pdf, doc, xls, ppt, docx, odt, ...

> Archive: zip, rar, 7z, tar, iso, ...

> Database: mdb, accde, frm, sqlite, ...

> Executable: exe, dll, so, class, ...

### 5.1.5 Common extensions that are text file formats:
> Web standards: html, xml, css, svg, json, ...

> Source code: c, cpp, h, cs, js, py, java, rb, pl, php, sh, ...

> Documents: txt, tex, markdown, asciidoc, rtf, ps, ...

> Configuration: ini, cfg, rc, reg, ...

> Tabular data: csv, tsv, ...
_________________
# 5.2.TEXT FILE CHARACTERISTICS
By convention, the data in every text file obeys a number of rules:
- The text looks readable to a human or at least moderately sane. Even if it contains a heavy proportion of punctuation symbols (like HTML, RTF, and other markup formats), there is some visible structure and it’s not seemingly random garbage.
- The data format is usually line-oriented. Each line could be a separate command, or a list of values could put each item on a different line, etc. The maximum number of characters in each line is usually a reasonable value like 100, not like 1000.
- The text looks readable to a human or at least moderately sane. Even if it contains a heavy proportion of punctuation symbols (like HTML, RTF, and other markup formats), there is some visible structure and it’s not seemingly random garbage.
###  5.2.1 BINARY FILE CHARACTERISTICS
-	For most software that people use in their daily lives, the software consumes and produces binary files. Examples of such software include Microsoft Office, Adobe Photoshop, and various audio/video/media players. A typical computer user works with mostly binary files and very few text files.
-	A binary file always needs matching software to read or write it. For example, an MP3 file can be produced by a sound recorder or audio editor, and it can be played in a music player or audio editor. But an MP3 file cannot be played in an image viewer or database software.
-	Some binary formats are popular enough that a wide variety of programs can produce or consume it. Image formats like JPEG are the best example – not only can they be used in image viewers and editors, they can be viewed in web browsers, audio players (for album art), and document software (such as adding a picture into a Word doc).
### 5.2.2 BASIC FILE OPERATIONS
> Creation of a new file

> Modification of data or file attributes

> Reading of data from the file

> Opening the file in order to make the contents available to other programs

> Writing data to the file

> Closing or terminating a file operation
_________________
# 5.3.READING TEXT FILES
-	To read a file in we need to open source file in read mode with a help of  open() function. 
-	Open() function requires two arguments that is 
o	file name (with path)
o	mode – specified as “r” to open in read only mode
-	And we need to call read() method then it will return file contents as string.
### 5.3.1 DEMO  CODE
Source.txt

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.3%201%202.png?raw=true)
![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.3%202.png?raw=true)
### Reading text files with size parameter 
-	To read a file in we need to open source file in read mode with a help of open() function. 
-	Open() function requires two arguments that is 
o	file name (with path)
o	mode – specified as “r” to open in read only mode
-	And we need to call read() method and pass size as parameter then it will return file contents (no of characters specified as size)  as string.
### 5.3.2 DEMO CODE
Source.txt

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.3%201%202.png?raw=true)
![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.3%20read%20size%20demo.png?raw=true)
### Reading text files (Single Line)
-	To read a file in we need to open source file in read mode with a help of open() function. 
-	Open() function requires two arguments that is 
o	file name (with path)
o	mode – specified as “r” to open in read only mode
-	And we need to call readline() method it will return first line as string.
-	readline() method uses ‘\n’ default delimiter.
### 5.3.3 DEMO CODE
Source.txt

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.3%20single%20line.png?raw=true)
![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.3%20single%20read%20line.png?raw=true)

### Reading text files (List of Lines)
-	To read a file in we need to open source file in read mode with a help of open() function. 
-	Open() function requires two arguments that is 
o	file name (with path)
o	mode – specified as “r” to open in read only mode
-	And we need to call readlines() method it will return list of strings (file contents).
-	readlines() method uses ‘\n’ default delimiter.
### 5.3.4 DEMO CODE
Source.txt

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.3%20single%20line.png?raw=true)
![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.3%20list%20of%20lines.png?raw=true)
_________________
# 5.4.WRITING TEXT FILES
-	To write contents in a file in we need to open destination file in write mode with a help of open() function.
-	Open() function requires two arguments that is 
o	file name (with path)
o	mode – specified as “w” to open in write only mode.
-	And we need to call write() method and pass file contents as arguments.
-	If destination it opens and overwrites new contents if not it will creates new destination file

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.4%20write%20demo.png?raw=true)
### 5.4.1 Types of File Modes
| File Mode  | Description  |
|---|---|
| r  | Opens a file for reading only. The file pointer is placed at the beginning of the file. This is the default mode.  |
| rb  | Opens a file for reading only in binary format. The file pointer is placed at the beginning of the file. This is the default mode.  |
| r+  | Opens a file for both reading and writing. The file pointer placed at the beginning of the file.  |
|  rb+ | Opens a file for both reading and writing in binary format. The file pointer placed at the beginning of the file.  |
| w  | Opens a file for writing only. Overwrites the file if the file exists. If the file does not exist, creates a new file for writing.  |
|  wb |  Opens a file for writing only in binary format. Overwrites the file if the file exists. If the file does not exist, creates a new file for writing. |
|  w+ | Opens a file for both writing and reading. Overwrites the existing file if the file exists. If the file does not exist, creates a new file for reading and writing.  |
| wb+  | Opens a file for both writing and reading in binary format. Overwrites the existing file if the file exists. If the file does not exist, creates a new file for reading and writing.  |
| a  | Opens a file for appending. The file pointer is at the end of the file if the file exists. That is, the file is in the append mode. If the file does not exist, it creates a new file for writing.  |
| ab  | Opens a file for appending in binary format. The file pointer is at the end of the file if the file exists. That is, the file is in the append mode. If the file does not exist, it creates a new file for writing.  |
| a+  |  Opens a file for both appending and reading. The file pointer is at the end of the file if the file exists. The file opens in the append mode. If the file does not exist, it creates a new file for reading and writing. |
|  ab+ |  Opens a file for both appending and reading in binary format. The file pointer is at the end of the file if the file exists. The file opens in the append mode. If the file does not exist, it creates a new file for reading and writing. |
### Difference between Append and Write Mode
-	Write (w) mode and Append (a) mode, while opening a file are almost the same. Both are used to write in a file. In both the modes, new file is created if it doesn’t exists already.
-	The only difference they have is, when you open a file in the write mode, the file is reset, resulting in deletion of any data already present in the file. While in append mode this will not happen. Append mode is used to append or add data to the existing data of file (if any). Hence, when you open a file in Append(a) mode, the cursor is positioned at the end of the present data in the file.
### File Methods
| File Methods  |  Description | Prototype  |
|---|---|---|
| close()  |  Closes the file |  fileobject.close() |
| flush() | Flushes the internal buffer  | 	fileobject.flush()    |
|  read() | Returns the file content  | data = fileobject.read()  |
| readable()  | Returns whether the file stream can be read or not  | boolean = fileobject.flush()  |
| readline()  | Returns one line from the file  | data = fileobject.readline()  |
| readlines()  | Returns a list of lines from the file  |  filelines = fileobject.read() |
| seek()  | Change the file position  |  filelines = fileobject.seek(offset) |
|  seekable() | Returns whether the file allows us to change the file position  |  bool = fileobject.seekable() |
| tell()  | Returns the current file position  |  position = fileobject.tell() |
| truncate()  | Resizes the file to a specified size  |  fileobject.truncate(size) |
| writeable()  | Returns whether the file can be written to or not  | bool = fileobject.writeable()  |
|  write() | Writes the specified string to the file  | fileobject.write(data)  |
| writelines()  | Writes a list of strings to the file  |  fileobject.writelines(listofstrings[]) |
### Tell in File
Python file method tell() returns the current position of the file read/write pointer within the file.

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.4%203.png?raw=true)
![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.4%204.png?raw=true)
### 5.4.2 Seek in File
Python file method seek() sets the file's current position at the offset. The whence argument is optional and defaults to 0, which means absolute file positioning, other values are 1 which means seek relative to the current position and 2 means seek relative to the file's end.
There is no return value. Note that if the file is opened for appending using either 'a' or 'a+', any seek() operations will be undone at the next write. If the file is only opened for writing in append mode using 'a', this method is essentially a no-op, but it remains useful for files opened in append mode with reading enabled (mode 'a+'). If the file is opened in text mode using 't', only offsets returned by tell() are legal. Use of other offsets causes undefined behavior.
### 5.4.3 DEMO CODE
Source.txt

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.4%203.png?raw=true)
![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.4%205.png?raw=true)
_________________
# 5.5.FORMAT OPERATOR
str.format() is one of the string formatting methods in Python3, which allows multiple substitutions and value formatting. This method lets us concatenate elements within a string through positional formatting.
Types
-	Single Place Holder
-	Multiple Place Holder
-	Type Specification

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.5.png?raw=true)
_________________
# 5.6.COMMAND LINE ARGUMENTS
The arguments that are given after the name of the program in the command line shell of the operating system are known as Command Line Arguments. We can use sys.argv to get and process the command line arguments
The sys module provides functions and variables used to manipulate different parts of the Python runtime environment. This module provides access to some variables used or maintained by the interpreter and to functions that interact strongly with the interpreter.

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.6.png?raw=true)

https://repl.it/@kiteit/GE8151-unit-programs#unit5/demo-cmd-args/main.py
_________________
# 5.7.ERRORS AND EXCEPTIONS
We can make certain mistakes while writing a program that lead to errors when we try to run it. A python program terminates as soon as it encounters an unhandled error. These errors can be broadly classified into two classes:

•	Syntax errors

•	Logical errors (Exceptions)

Error caused by not following the proper structure (syntax) of the language is called syntax error or parsing error.

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.7.png?raw=true)
_________________
# 5.8. HANDLING PYTHON LOGICAL ERRORS (EXCEPTIONS)

[EXCEPTIONS](https://www.tutorialspoint.com/python/python_exceptions.htm)
Errors that occur at runtime (after passing the syntax test) are called exceptions or logical errors.
For instance, they occur when we try to open a file(for reading) that does not exist (FileNotFoundError), try to divide a number by zero (ZeroDivisionError), or try to import a module that does not exist (ImportError).
Whenever these types of runtime errors occur, Python creates an exception object. If not handled properly, it prints a traceback to that error along with some details about why that error occurred.

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.8.png?raw=true)
# 5.8.1 BUILD IN EXCEPTIONS
| Exception  | Cause of Error  |
|---|---|
| AssertionError  | Raised when an assert statement fails.  |
| AttributeError  |  Raised when attribute assignment or reference fails. |
|  EOFError |  Raised when the input() function hits end-of-file condition. |
|  FloatingPointError | Raised when a floating point operation fails.  |
| GeneratorExit  |  Raise when a generator's close() method is called. |
| ImportError  | Raised when the imported module is not found.  |
| IndexError  | Raised when the index of a sequence is out of range.  |
| KeyError  |  Raised when a key is not found in a dictionary. |
| KeyboardInterrupt  | Raised when the user hits the interrupt key (Ctrl+C or Delete).  |
| MemoryError  | Raised when an operation runs out of memory.  |
| NameError  |  Raised when a variable is not found in local or global scope. |
| NotImplementedError  |  Raised by abstract methods. |
| OSError  | Raised when system operation causes system related error.  |
| OverflowError  | Raised when the result of an arithmetic operation is too large to be represented.  |
|  ReferenceError | Raised when a weak reference proxy is used to access a garbage collected referent.  |
| RuntimeError  | Raised when an error does not fall under any other category.  |
| StopIteration  |  Raised by next() function to indicate that there is no further item to be returned by iterator. |
| SyntaxError  | Raised by parser when syntax error is encountered.  |
| IndentationError  | Raised when there is incorrect indentation.  |
|  TabError |  Raised when indentation consists of inconsistent tabs and spaces. |
|  SystemError |Raised when interpreter detects internal error.   |
|  SystemExit | Raised by sys.exit() function.  |
| TypeError  |  Raised when a function or operation is applied to an object of incorrect type. |
| UnboundLocalError  |  Raised when a reference is made to a local variable in a function or method, but no value has been bound to that variable. |
| UnicodeError  | Raised when a Unicode-related encoding or decoding error occurs.  |
|UnicodeEncodeError   |  Raised when a Unicode-related error occurs during encoding. |
|UnicodeDecodeError   | Raised when a Unicode-related error occurs during decoding.  |
| UnicodeTranslateError  |  Raised when a Unicode-related error occurs during translating. |
|  ValueError | Raised when a function gets an argument of correct type but improper value. |
| ZeroDivisionError  | Raised when the second operand of division or modulo operation is zero.  |
# 5.9. MODULES
A module allows you to logically organize your Python code. Grouping related code into a module makes the code easier to understand and use. A module is a Python object with arbitrarily named attributes that you can bind and reference.
Simply, a module is a file consisting of Python code. A module can define functions, classes and variables. A module can also include runnable code.

[MODULES](https://www.tutorialspoint.com/python/python_modules.htm)

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.9%201.png?raw=true)
### Illustrative Problems (Copy File)

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.9%202.png?raw=true)
### Illustrative Problems (Word Count)

![N|Solid](https://github.com/SubasriNatarajan/python/blob/main/5.9%203.png?raw=true)


























