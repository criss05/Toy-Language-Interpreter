# ToyLanguageInterpreter
This Java-based interpreter processes user-input operations using custom-built data structures and types. It features a GUI for easy interaction and supports arithmetic computations, variable assignments, and more. Developed as a faculty project, it showcases concepts in language design and software engineering.


# First Step
This Java-based interpreter models a custom programming language with user-defined data structures (stack, map, list) and data types (int, bool, string). It supports statements like assignment, conditionals, no-op, print, and variable declaration, along with expressions for logic, relations, arithmetic, variables, and values. The project includes a program state to manage the execution stack, variable table, and output list. Actions are controlled by a central controller, and a console-based view allows users to interact with the interpreter. The project is organized in a repository that handles program states and action execution.


#  Second Step
In this step, a file table was implemented to track all open files within the program. New statements were added to the interpreter to support file operations, including opening, closing, and reading text from files. This enhancement allows the interpreter to interact with external files, expanding its functionality beyond basic in-memory operations. The file table efficiently manages and monitors the state of open files during execution.

# Third Step
In this step, a heap data type was introduced to manage dynamically allocated variables. The symbol table was extended to allow variables to reference locations in the heap, where the actual data is stored. Additionally, a garbage collector was implemented to periodically scan both the heap and symbol table, identifying and deleting variables that are no longer in use. This ensures efficient memory management and prevents memory leaks, enhancing the overall performance and reliability of the interpreter.

# Forth Step
In this step, the interpreter was extended to support concurrent execution of multiple programs. A for statement was introduced to create new program states, allowing the interpreter to run multiple instances in parallel. This enhancement enables the execution of concurrent tasks within the same interpreter environment, increasing flexibility and expanding the functionality of the language.

# Almost last step
In this step, a type checker was added to the interpreter to ensure type safety in program execution. The type checker verifies that all operations and expressions are type-compatible before execution, returning an error if there are any mismatched types or invalid operations. This feature improves the reliability of the interpreter by preventing runtime type errors and ensuring that only valid programs are executed.

# Last Step
In the final step, a graphical user interface (GUI) was implemented to provide an intuitive way for users to interact with the interpreter. The GUI displays a list of all available programs, allowing the user to select one for execution. Upon selection, a window appears showing detailed information, including the program's variable tables, output list, execution stack, and a list of all program state IDs. This GUI enhances the user experience by providing a visual representation of the program’s internal state and making it easier to monitor and manage the execution of multiple programs.

