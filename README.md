# langchain_llm
Langchain end to end projects

## Set up virtual env

**Approach 1** <br />
Conda to create venv
Advantage: 
- All the packages and env are properly managed through Anaconda
- It helps to create env with Python version directly even when base version is different.
Disadvantage: Conda needs to be installed.
### Through anaconda prompt
- $ conda create -p langchain_env  python=3.9 -y 

### Through VS code or PyCharm
1. open cmd from terminal (!! check its not powershell !!)
2. $ conda create -p venv  python=3.9 -y  
   - This will creat a folder venv/
3. Activate the env: $ conda activate venv/

**If conda is not recognised** 
check conda is recognised or not
    $ conda --version
    if not, ensure conda is in PATH, steps 
-   Open the Start menu, search for "Edit the system environment variables," and open it.
-   Click on "Environment Variables."
-   In the "System variables" section, select the "Path" variable and click -   "Edit..."
-   Add the directory where Conda is installed (usually something like C:\Users\YourUsername\Miniconda3\Scripts or C:\Users\YourUsername\Anaconda3\Scripts).
where conda.exe is located.
-   Click "OK" to save the changes and close the windows.
3. Activate the base conda environment
$ conda actiivate base
OR
$ C:\Users\YourUsername\Anaconda3\Scripts\activate base
4. Now create the virtual env again
$ conda create -p langchain_env  python=3.9 -y

**Approach 2** <br />
Direct python 
Advantage: 
- When conda is not installed
Disadvanatge :
- Installing different python version is little complicated

### Through cmd (even in VS Code)
1. Create a venv with folder name myenv in wd
  $ python -m venv myenv
   Here env name is **myenv**, will create a folder with name myenv.
2. Activate the env: $ myenv/Scripts/activate
3. $python --version --> Default version installed in my system
* If I need to upgrate to different python version, need to download that version from www.python.org first then install it and create env.

**Approach 3** <br />
Popular in LINUX command
1. Install virtualenv
  $ pip install virtualenv
2. Create venv using virtualenv
  $ virtualenv -p python3 venv
   Here env name is **venv**, this will create a folder with name venv.
3. Activate the env: $ venv/Scripts/activate
* If I need to upgrate to different python version, need to download that version from www.python.org first then install it and create env.
  
