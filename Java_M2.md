- L3 Basics
  - whitespace
    - blanks, tabs, newline characters
  - commenting
  - errors
    - compiler
    - runtime errors
      - stack trace
    - logical
      - fulling run, but unwanted results
    - Syntax vs Semantics
      - Syntax
        - reserve words
        - identifiers
        - other symbols
      - Semantics
        - the meaning of code
  - Comments
    - Line Comments
    - Block (or multi-line comments)
    - Javadoc comments

  - Variables and Constants
  - Primitive types
    - integer
      - byte
      - short
      - int
      - long
    - Real Number Values
      - float
      - double
    - characters
      - char (single quote) (escapte sequence \')
    - Logic based Values
      - boolean
  - Default Types
  - expressions
  - casting
    - precedence: parenthessis > casting > others

- L4 Using Predifined Classes
  - Declare variables
  - Instantiation
    - the process of creating an object
    - new Class (parameters)
  ```
  String major:
  major = new String ("Computer Science")

  ```
- Invoking Methods

  - identifier.methodName(parameters)
    - print
    - println
    - length
  - More on Reference variables
    - alias
      - two variables point to the same Object
        - ```

        major = 'Computer Science'
        interest = 'Computer Science'
        major.length() = interest.length
        ```
   - object with no variables point to
     - garbage collection
- String method
  - ```

  concat(String)
  replace(oldChar, newChar)
  substring(int,int) #string index starts at 0
  toLowerCase()
  ```
- calling Object
- ```

  "Computer Science".toLowerCase()

  ```
- concat (Pass by Value)
```
String major = "Computer Science";
String interest = "long walk on the beach";
major.concat(interest)
```
Return "Computer Sciencelong walks on the beach"

- L5 Input and Output
  - Scanner 
