# psview
View information of system processes

## Getting Started
These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites
Things you will need to install for this program.
- Python
- psutils
- Linux/Unix

**Note:** This tool is only supported on Linux/Unix operating system.

### Installing
Activate virtual environment
```
source bin/activate
```
Run the following command
```
pip install -r requirements.txt
```

## Usage
Enumerate all the running processes.
```
./psview.py -p, --enum_proc
```

List all the running threads within process boundary.
```
./psview.py -t pid, --threads pid
```

Enumerate all the loaded modules within the processes.
```
./psview.py -l pid, --loaded_modules pid
```

Is able to show all the executable pages within the processes.
```
./psview.py -e pid, --executable_pages pid
```

Gives us a capability to read the memory.
```
./psview.py -m pid, --mem_info pid
```

Help
```
./psview.py -h, --help
```
