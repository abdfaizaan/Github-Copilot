# Exercise 2: Exploring AI-Driven Code Suggestions in JavaScript

### Estimated Duration: 20 minutes

While GitHub Copilot offers recommendations for many languages and frameworks, it excels in particular when it comes to Python, JavaScript, TypeScript, Ruby, Go, C#, and C++. The samples below are in JavaScript, but they should also work in other languages.

In this lab, you will have the opportunity to experiment with and apply JavaScript with the assistance of GitHub Copilot and GitHub Copilot Chat.

> **Disclaimer**: GitHub Copilot will automatically suggest the entire body of a function in gray text. However, the precise recommendation may vary.

> **Note**: If you can't see any GitHub Copilot hints in VS Code, restart VS Code once and try again.

## Lab objectives

In this lab, you will complete the following tasks:

- Task 1: Add a JavaScript file and start writing code

## Task 1: Add a JavaScript file and start writing code

1. In the LABVM desktop, select Visual Studio Code.
 
1. From the VS Code Explorer window, create a New File.

   ![](../media/E2T1S2-0807.png)

1. Name the file `skills.js` and verify your new file looks as shown below:
   
   > **Note:** Create the `skill.js` file outside the `.devcontainer` folder.

      ![](../media/E2T1S3-0807.png)

1. In the `skills.js` file, type the following function header and press `Enter` to see the code suggestions.

   ```
   // function to covert Celsius
   // to Fahrenheit
   ```
   
   > **Note**: A whole function body will be automatically suggested by GitHub Copilot in gray text. Here's an example of what you are likely to see; however, the precise recommendation could vary.

   ![](../media/skillsjs1-0303.png)

1. Press `Tab` to accept the suggestion.

   ![](../media/py61.png)

   > **Note**: You might need to press the tab again to see the suggestions and accept them.
  
1. In the next line, type the following:

   ```
   // Driver code
   ```
   ![](../media/py62.png)

1. Press  `Enter` and `Tab` to accept the suggestion, and then press `Ctrl + S` to save the file.

      ![](../media/py63.png)

     > **Note**: However, it should be noted that the suggestions from GitHub Copilot may vary, necessitating a clear understanding of the Javascript code and its usage.

1. Click on the **ellipsis (1)** on the top, click on **Terminal (2)** and select **New Terminal (3)**.

   ![](../media/openterminal.png)     
   
1. Run the application with the command mentioned below in the terminal and verify that the output has been generated.

   ```
   node skills.js
   ```

   ![](../media/E2T1S9-0807.png)

    >**Note**: You can also try the same commands to convert from Fahrenheit to Celsius as shown below:

     ![](../media/py24.png)

     ![](../media/py26.png)

   >**Note**: Wait about 60 seconds, then refresh your GitHub repository landing page for the next step.

   > **Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
   > - Hit the Validate button for the corresponding task. If you receive a success message, you can proceed to the next task.
   > - If not, carefully read the error message and retry the step, following the instructions in the lab guide. 
   > - If you need any assistance, please contact us at cloudlabs-support@spektrasystems.com. We are available 24/7 to help you out.

   <validation step="6792c557-2d4b-43ce-a904-427d7a72f16d" />

## Review
In this lab, you have effectively created JavaScript code and pushed it from the production branch to the main branch.

## You have successfully completed the lab. Click on **Next >>** to procced with next exercise.
