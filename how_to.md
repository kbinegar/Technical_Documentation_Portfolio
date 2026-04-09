## How to Open a Local Git Repository in Visual Studio Code (macOS/Linux)
### Prerequisites
- Git is installed and available in Terminal (`git --version`)
- Visual Studio Code is installed
- A local Git repository exists on your machine

1. **Enable the `code` command in Terminal**  
     This makes VS Code available to Terminal   

    &emsp;&emsp;In VS Code:
    1. Press: Cmd + Shift + P  
    2. Search for:  
        `Shell Command: Install 'code' command in PATH`  
    3. Press: Enter      
  
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
    