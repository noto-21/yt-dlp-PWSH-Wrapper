<hr>

<div align="center">

# yt-dlp PWSH Wrapper
A wrapper for the somewhat confusing and oft overcomplicated yt-dlp binary. Assumes that you have yt-dlp and node already installed.

### Shell Command
Can be placed in `/usr/local/bin` (with `sudo`) to be used with the shell.  If problems with running occur, try to change execution permission via `sudo chmod +x /usr/local/bin/exam`.

## SQLite Database
The `exam.db` file will be stored in `/home/<username>/.config` on Linux, and `C:\Users\<username>\AppData\Local` on Windows.

## Flags

</div>

```
usage: exam [-h] {insert,show,delete} ...
                        
Exam Scheduler using SQLite3
                        
positional arguments:
	{insert,show,delete}
		insert              Insert a new exam record
		show                Show all exams
		delete              Delete exams for a course
                        
options:
	-h, --help            show this help message and exit
```

<div align="center">

## Dependencies

</div>

### Python Packages
If you want to use a virtual environment, please run `pip install -r requirements.txt` to install all necessary packages, or feel free to install each library individually:

- colorama: Library for colored terminal text output.  Install using `pip install colorama`.
- tabulate: Library for tabular formatted output.  Install using `pip install tabulate`.

<hr>
