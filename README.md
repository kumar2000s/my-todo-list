# my-todo-list written in RUST

how to buid and run

Step-1: clone the repo
Step-2: go to clone directory
Step-3: cargo build --release

----------------------------------------------------
PS C:\my-todo-list\target\release> .\my-todo-list.exe -h   
Rusty Journal 0.1.0
A command line to-do app written in Rust

USAGE:
    my-todo-list.exe [OPTIONS] <SUBCOMMAND>

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -j, --journal-file <journal-file>    Use a different journal file

SUBCOMMANDS:
    add     Write tasks to the journal file
    done    Remove an entry from the journal file by position
    help    Prints this message or the help of the given subcommand(s)
    list    List all tasks in the journal file
    
------------------------------------------------------------
    
Example to add task
    
C:\my-todo-list\target\release> .\my-todo-list.exe -j mytodolist.json "my first task"
