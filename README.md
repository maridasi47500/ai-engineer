## Examples and exercises from the book "Python for AI Engineers"
- do 
````
sh mysite.sh
````
- tu dois faire un truc qui s'appelle answers / examples: 
````
..
04_data_structures
Hey
7 months ago
05_basic_scripts
Hey
7 months ago
06_control_structures
Hey
7 months ago
07_files
````

- do
````

task_4_1.py
Hey
7 months ago
task_4_2.py
Hey
7 months ago

````

- do 
````
python3 Task
````
- gem pour quel langage informatique

[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/) [![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)

All examples and exercises have been tested in Python 3.7 and 3.8.
> All tasks are focused on AI  topics.

## Links

* [Working environment](https://pyneng.readthedocs.io/en/latest/book/01_intro/work_env.html)
* [Testing tasks with the pyneng utility](https://pyneng.readthedocs.io/en/latest/book/additional_info/pyneng.html)

## How to create your own repository for tasks

> [Git/Github basics](https://pyneng.readthedocs.io/en/latest/book/02_git_github/index.html)



### Clone repository

To work locally with the repository, you need to clone it.
To do this, use the git clone command:

```
$ git clone git@github.com:anonyme/my_tasks.git
Cloning into 'my_tasks'...
remote: Counting objects: 241, done.
remote: Compressing objects: 100% (191/191), done.
remote: Total 241 (delta 43), reused 239 (delta 41), pack-reused 0
Receiving objects: 100% (241/241), 119.60 KiB | 0 bytes/s, done.
Resolving deltas: 100% (43/43), done.
Checking connectivity... done.
```

In the command output above, you need to change:

- username natenka to your username on GitHub
- repository name my_tasks to the name of your repository

As a result, in the current directory where the git clone command was executed,
a directory with the name of the repository will appear, in my case -
"my_tasks". This directory now contains local copy of the repository with tasks.

## Tasks (exercises)

The exercises directory contains tasks with numbers corresponding to the sections of the book.
In addition, there are all additional files (configurations, etc.) that are used in tasks.

## Tests

Starting from section “4. Data types in Python ”there are automated tests for testing tasks.
They help to check whether everything matches the task, and also give feedback on what does not correspond to the task.
As a rule, after the first period of adaptation to tests, it becomes easier to do tasks with tests. Testing is done using the pyneng utility.

[Learn more about how to work with the pyneng utility](https://pyneng.readthedocs.io/en/latest/book/additional_info/pyneng.html).

