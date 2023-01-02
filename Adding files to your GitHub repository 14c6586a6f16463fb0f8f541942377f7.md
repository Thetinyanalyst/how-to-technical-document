# Adding files to your GitHub repository

Follow these guidelines to upload files to your GitHub repository.

**Create a remote repository**

- Log into your GitHub account and create your repository.
- Set the visibility to Public or Private.

![Screenshot 2023-01-01 084050.png](Adding%20files%20to%20your%20GitHub%20repository%2014c6586a6f16463fb0f8f541942377f7/Screenshot_2023-01-01_084050.png)

<aside>
💡 There are two ways to upload files to your repository. Based on your requirements you can select the method.

</aside>

1. **Direct upload**
    - Select **Create** to add new files to your repository.
    - Select **Upload** to ****add existing files to your repository.
    

![Screenshot 2023-01-01 084542.png](Adding%20files%20to%20your%20GitHub%20repository%2014c6586a6f16463fb0f8f541942377f7/Screenshot_2023-01-01_084542.png)

<aside>
💡 Use this method if your folder does not contain multiple files in it or is a singular file.

</aside>

1. **Upload using git**
    - Download git locally to your system from [https://git-scm.com/](https://git-scm.com/)
    - Open command prompt and check the version of Git
    
    ```powershell
    > git --version
    ```
    
    - Go to the location of your project and initialize the new git repository
    
    ```powershell
    > cd <project name>
    > git init
    ```
    
    - Add your files
    
    ```powershell
    > git add <file>
    ```
    
    - Commit changes to the local repository
    
    ```powershell
    > git commit -m “first commit”
    ```
    
    - Set the location of your remote repository
    
    ```powershell
    > git remote add origin <repo url>
    ```
    
    - Push to remote repository
    
    ```powershell
    > git push -u origin <branch name>
    ```
    

To see the changes on your remote repository simply refresh the page.

[Note to the reader](https://www.notion.so/Note-to-the-reader-efa7e6a1fefd4d9483721c5dee15409a)