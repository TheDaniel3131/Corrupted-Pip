# Corrupted-Pip
This is an informative repo dedicated to everyone with the same problem as mine. 
Note: this is not my solution, all credits and kudos belong to those who shared these wonderful solutions on StackOverflow & Blogs. 

Such Problems (like pip's import error, py/python's unable to create process, etc.):
<br>
https://www.alphr.com/pip-is-not-recognized-as-an-internal-or-external-command/
<br>
https://stackoverflow.com/questions/37220055/pip-fatal-error-in-launcher-unable-to-create-process-using

<br>

### Solution:

1. Open your command line terminal and run this command    
```cmd
python -m ensurepip --default-pip
```
<br>

2. Download the get-pip.py file.
<br>

3. Save your get-pip.py to any folder and copy the file directory, then paste it to the terminal and run the following command
```cmd
cd C:\>python get-pip.py
```

<br>

4. And you are good to go! Please check if you have pip installed by typing this command
```cmd
pip --version
```

<br>

Also check python version as well!!!
```cmd
python --version
```

or

```cmd
py --version
```

<br>

If you have another problem like mine case which I can show it to you below. 
```cmd
C:\Python\get-pip>py main.py
Unable to create process using '"C:\Program Files\Python311\python.exe"  main.py': The system cannot find the file specified.
```

<br>

In my case, I uninstalled Python v3.11 but py is still finding it no matter what. To do that, we just have to use 'doskey' command
```cmd
doskey py = python
```

<br>


### EVERYTHING IS GOOD OT GO!!!!!!
   
<br>


References:
https://stackoverflow.com/questions/23708898/pip-is-not-recognized-as-an-internal-or-external-command

Follow this one to deal with corrupted pip:
http://www.cosonok.com/2022/08/windowspython-fixing-corrupted-pip-file.html
