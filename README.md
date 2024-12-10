# langchain_llm
Langchain end to end projects

## Set up virtual env

# Through anaconda prompt
- $ conda create -p langchain_env  python=3.9 -y 

# Through VS code or PyCharm
1. open cmd from terminal (!! check its not powershell !!)
2. check conda is recognised or not
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
