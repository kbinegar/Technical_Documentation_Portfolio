## How to Open a Local Git Repository in Visual Studio Code (macOS/Linux)
### Prerequisites
- Git is installed and available in Terminal (`git --version`)
- Visual Studio Code is installed
- A local Git repository exists on your machine

1. **Allow Visual Studio Code (VS Code) to open repositories from Terminal**  
    To do so, enable the 'code' Terminal command in VS Code.   

    &emsp;&emsp;In VS Code:
    1. Press: Cmd + Shift + P  
    2. Type:  
        `Shell Command: Install 'code' command in PATH`  
    3. Press: Enter   
    
    Now VS Code is availble to Terminal when opening files/folders
  
2. **Open your repository in Terminal**  
    Navigate to your repo in Terminal using:  

    `cd ~/path/to/your/repo`

3. **Once inside, run:**  

    `code .`

    The '**.**' opens the current folder  
    This will prompt VS Code to open the selected repository  
    You will now see your repositorty in a VS Code window:  
    ```
    Repo_Name  
    ├── README.md  
    ├── file.md  
    └── .git
    ```

4. **Click on your file to open & edit**
    