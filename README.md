# Personal Finance Tracker

A group project as part of the Computer Programming (COMP 2603) module. The Team consists of:

1. Sofia Linardou (A00042850)
1. Luke Kearns ()

### Project Guidelines

The classic three-tier architecture should be employed:

- Presentation Layer: C++ (command prompt for entering and printout)
- Application Layer: C++ code (algorithms and calculations)
- Storage (persistence layer): files

## Project Scope

As per the given document the second task was chosen.
The Personal Finance Tracker _"An application to help users manage their finances, track expenses, and generate reports."_ where the below is possible:

- User account creation and login
- Add, edit, and delete income and expense entries
- Categorize expenses (e.g., food, entertainment)
- Generate monthly/annual spending reports
- Save data to a file for future use

There are four main stages to the tackling the project scope

1. user account/s
1. income and expenses
1. categories
1. financial statements (persistence layer)

### User Stories

To allow for easy management of tasks and to ensure the all aspects of the scope are met timely, 'user stories' will be used. These will make up the tasks necessary in the board.

<u>_As a new user, I can_:</u>

- create an account
- add income and expense entries
- edit income and expense entries
- delete income and expense entries
- create categories
- edit categories
- delete categories
- assign categories to my expenses
- save data to a file for future use

<u>_As an existing user, I can_:</u>

- login into my account
- add income and expense entries
- edit income and expense entries
- delete income and expense entries
- create categories
- edit categories
- delete categories
- assign categories to my expenses
- save data to a file for future use
- delete my account

## Source Code

### Repository Structure

Directories are made to house specific types of files used in the code.

1. Header files

### Coding Guidelines

All code must be peer-reviewed before merging. This includes reading and understanding the program structure, manual testing and whether the code is in the correct format.

As per the [C++ coding guidelines](https://github.com/Microsoft/AirSim/blob/main/docs/coding_guidelines.md):

#### Naming Conventions

Naming conventions should be consistent across the codebase.
Code Element | Style
---- | ----|
Namespace | `snake_case`
Class name | `PascalCase`
Function name | `camelCase`
Parameters/Locals | `snake_case `
Member variables | `snake_case`
Constant variables | `SCREAMING_SNAKE_CASE`
Enums and its members | `PascalCase`
Globals | `g_snake_case` |
File names | Match case of class name in file|

#### Bracketing

Inside function or method body place curly bracket on same line. Outside that the Namespace, Class and methods levels use separate line. For example:

```cpp
int main()
{
    int x = 0;
    if (x < 10) {
        x++;
    } else {
        x--;
    }
}
```
