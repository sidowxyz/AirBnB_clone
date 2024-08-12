# AirBnB Clone - The Console

This project is part of the AirBnB clone project, which is about building a complete web application that mimics the functionality of the famous AirBnB website from the back-end to the front-end. This particular part, "The Console," involves creating a command interpreter in Python to manage AirBnB objects. This is the first step towards building the full web application.

## Project Details
- **Weight:** 5
- **Project duration:** May 13, 2024, 6:00 AM to May 20, 2024, 6:00 AM
- **Team Members:** SIDOW ADAN SIDOW and Patience Ayirezang
- **Manual QA Review Date:** May 29, 2024, 11:40 AM
- **Auto QA Review:** Conducted at the deadline

### Overall Results
- **Contribution:** 100.0%
- **Manual QA Review:** 0.0/48 mandatory
- **Auto QA Review:** 141.5/302 mandatory & 116.5/233 optional
- **Final Score:** 60.65%

## Background Context

The goal of "The Console" is to create a command interpreter to manage AirBnB objects, including their creation, retrieval, updating, and destruction. This part lays the groundwork for the upcoming projects that will incorporate HTML/CSS templating, database storage, API, and front-end integration.

## Usage

The command interpreter is launched in interactive mode like this:

```bash
$ ./console.py
(hbnb)
```

The console can also be used in non-interactive mode by piping echo statements into it:

```bash
$ echo "help" | ./console.py
(hbnb)
```

### Commands

- `quit` and `EOF`: Exit the console
- `help`: Provides descriptions of commands
- `create`: Creates a new object (e.g., `create User`)
- `show`: Shows an object (e.g., `show User <id>`)
- `destroy`: Deletes an object (e.g., `destroy User <id>`)
- `all`: Displays all objects of a class or all objects
- `update`: Updates an object (e.g., `update User <id> name "John Doe"`)

### Examples

Start the console:

```bash
$ ./console.py
```

Create a new user:

```bash
(hbnb) create User
```

Show an existing user:

```bash
(hbnb) show User 1234-1234-1234
```

Delete a user:

```bash
(hbnb) destroy User 1234-1234-1234
```

Update a user:

```bash
(hbnb) update User 1234-1234-1234 email "user@example.com"
```

## Setup

To run the console:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/AirBnB_clone.git
    ```

2. Access the project directory:

    ```bash
    cd AirBnB_clone
    ```

3. Run the console in interactive mode:

    ```bash
    ./console.py
    ```

## Contributors

This project was created by SIDOW ADAN SIDOW and Patience Ayirezang. The complete list of contributors can be found in the `AUTHORS` file.

---

Make sure to adjust paths or URLs as necessary, and replace placeholder links with actual URLs where your project is hosted.
