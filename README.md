## Sync.py

#### Description:
* The script synchronizes two directories - the source and the replica. 
* Synchronization is one-way, the contents of the replica directory are converted to the contents of the source.
* Copy and delete operations are logged to a file and output to the console.

* The paths to directories, the synchronization interval and the path to the log file are set by command line parameters when starting the program.

#### Technologies used:
* Only standard Python libraries are used.
  
#### How to use:

* Clone the repository and go to it on the command line:
```bash
git clone https://github.com/feyaschuk/test_task_2.git
```
```bash
cd test_task_2
```

* Run the program:
```bash
python sync.py (source directory path) (replica directory path) (interval) (path to the log file)
```
#### Example of use:
```bash
python sync.py 'C:\Users\user\Dev\xz' 'C:\Users\user\Dev\test' 5 'C:\Users\user\Dev\sprint13\Log.log'
```
#### Notice:
* For Windows users - paths to directories and the path to the log file must be specified in quotation marks.
* The restart interval is in seconds
