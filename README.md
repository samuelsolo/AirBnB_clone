# AirBnB Clone Project

## Project Description:
Welcome to the AirBnB Clone Project! This is the first half of the project, aimed at creating a command interpreter to manage AirBnB objects. It serves as the foundation for building a fully functional AirBnB replica.

## Command Interpreter Description:
### How to Start:
To start the command interpreter, simply run the `console.py` script using Python 3.8.5 or later.

```bash
$ ./console.py
```

### How to Use:
Once the command interpreter is started, you can interact with it using various commands. Here are some of the available commands:

- `create <class_name>`: Create a new instance of the specified class.
- `show <class_name> <object_id>`: Show details of a specific object.
- `update <class_name> <object_id> <attribute_name> <attribute_value>`: Update the attributes of a specific object.
- `destroy <class_name> <object_id>`: Delete a specific object.
- `all <class_name>`: Show details of all objects of a specific class.
- `quit` or `EOF`: Exit the command interpreter.

### Examples:
- To create a new User object:
```bash
(hbnb) create User
```

- To show details of a specific Place object:
```bash
(hbnb) show Place 1234-5678-9012
```

- To update the name attribute of a State object:
```bash
(hbnb) update State 9876-5432-1098 name "New York"
```

- To delete a specific object:
```bash
(hbnb) destroy City 2468-1357-7910
```

