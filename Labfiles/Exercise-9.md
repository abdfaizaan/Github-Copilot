# Exercise 9: Generating Documentation Using GitHub Copilot [Optional]

### Estimated Duration: 10 minutes

GitHub Copilot can help streamline the process of generating documentation for your software projects. It assists by auto-generating code comments, creating Markdown documentation, providing templates for common sections, ensuring grammar and style consistency, and cross-referencing code and documentation. This tool can save time and improve the quality of your project's documentation, making it more accessible and user-friendly.

In this exercise, you will be generating documentation using GitHub Copilot.

>**Disclaimer**: GitHub Copilot will automatically suggest an entire function body or code in grayed text. Examples of what you'll most likely see in this exercise, but the exact suggestion may vary.

>**Note**: If you are unable to see any suggestions by GitHub Copilot in VS Code, please restart VS Code once and try again. 

## Lab objectives

You will be able to complete the following tasks:

- Task 1: Generate a README file with GitHub Copilot using comments
- Task 2: Push code to your repository from the codespace

### Task 1: Generate a README file with GitHub Copilot using comments

1. From inside the codespace in the VS Code Explorer window, create a new file and name the file as `Document.md`.

    ![](../media/chat-code-new.png)

1. Press `CTRL + I` to provide statements to GitHub Copilot.

1. Provide the below statement **(1)** for the GitHub Copilot to create a document that shows the creation of the sample Node.js application. Hit **Send (2)**.

    ```
    Create a markdown document for a sample Node.js application with Mermaid diagrams and reference links
    ```

    ![](../media/E9T1S3-0807.png)

1.  Copilot will give a response, and you can review it, click **Accept**, and press `CTRL + S` to save the file.

    ![](../media/E9T1S4-0807.png)

1.  Observe how Copilot has generated the Mermaid diagrams and included the reference links as per our request.

    ![](../media/E9T1S5.1-0807.png)
    
    ![](../media/E9T1S5.1-0807.png)

### Task 2: Push code to your repository from the codespace

1. Open a terminal and run the following command to add the files :

    ```
    git add .
    ```
1. Run the below command to commit the files :

    ```
    git commit -m "files"
    ```

1. Execute the command below to commit the files. Copy your GitHub user email and paste it inside the quotes.

   ```
   git config --global user.email "<inject key="AzureAdUserEmail" enableCopy="true"/>"
   ```

1. Run the command below to commit the files, replacing "xxxx" with the number in the email.

   ```
   git config --global user.name "<inject key="GitHub User Name" enableCopy="true"/>_clabs"
   ```

1. Run the below command to push all the files to the repository :

    ```
    git push
    ```
    
## Summary

In this exercise, you have successfully generated a document using GitHub Copilot Chat and pushed the code to your repository.

## You have successfully completed the lab. Click on **Next >>** to proceed with the next exercise.
