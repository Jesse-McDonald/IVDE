# IVDE
Integreated Video Development Environment (IVDE) Is an "IDE" specifically made for creating a Videos of an "ide" 
It should be noted that IVID is not an IDE, but will have the appearance of being an ide that a skilled programmer is using.
IVID (will) features a visual code window, an interpreter for several languages (java, c/c++, python3), a memory viewer for the interpreter, and a code output window

#Visual Code Window
This "text editor" takes a TSCF (Time stamped Code Format) to automatically "type" code at specific times.  
The window also features a code execution hilighter for the interpreter and a multiple selector where multiple arbitrary lines of code can be selected for changing.
For more on what is possible, see the desciptor of the TSCF format

#Code Interpreter
Just like it says on the box, the code interpreter will take code written in java, c++, or python3 and execute it line by line.
using a TSCF generated eval String it is also possible to prefor exucutions of part of a line or to pause specific lines for a time.
The interpreter is not feature complete.  As I use a new feature of the language I will add it to the interpreter.
The code Interpreter may also use Javac or gcc to validate the code and generate errors.

#Memory Viewer
Provides real time view into the memory space of the Interpreter
Can provide variable tables, arrays, and pointer arrows
Also can hilight sections of memory depending on interpreter

#Code visualization output
This box can range from the terminal output of a cmd program being executed to the visual output of a program.  
