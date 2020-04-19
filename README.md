# Os-file-system
OS Project : Simple file manager that uses a simulated partition (UNIX file) as support to store files and directories. 

## Getting started
### Installing and compile
To install this project:
First download the project from :
```
git clone https://github.com/Anclaguedon/Os-file-system
```

Then go to the directory
```
cd os_project
```

Compile source code and generate docs
```
make
make gendocs
```
To run
```
./programme
```

## File system structure
<img src="https://github.com/Anclaguedon/Os-file-system/blob/master/docs/file_system_structure.png" width="290" height="530">
The partition (Unix file) is divided into N blocks of equal size.
