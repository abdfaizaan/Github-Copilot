# Exercise 7: Enhancing Web Accessibility with GitHub Copilot Chat and Accessibility Insights

### Estimated Duration: 35 minutes

**GitHub Copilot Chat** is an AI-powered code completion tool that helps developers by suggesting code snippets and solutions based on context. This tool can significantly speed up the development process by providing relevant code suggestions and automating repetitive tasks.

**Accessibility Insights for Web** is a powerful, user-friendly tool to ensure web content is accessible to everyone, including those with diverse abilities. By integrating this tool into the development and testing process, web developers can ensure their websites meet accessibility standards, enhancing usability and inclusivity.

Accessible University (AU) is a fictional university home page designed to demonstrate a variety of common web design problems that result in visitors with disabilities being unable to access content or features.

Use the AU site to:

1. Demonstrate common web accessibility principles at trainings, presentations, and workshops on accessible web design.
   
1. Learn common web accessibility problems and solutions in an easy-to-understand way.

In this exercise, you will use Accessibility Insights for Web to identify accessibility issues on a sample website and then employ GitHub Copilot Chat to generate and implement code fixes for these issues. The target website, Accessible University (AU), is a fictional homepage designed to showcase common web design problems that hinder accessibility. By the end of this exercise, you will have enhanced the accessibility of the AU site, making it more user-friendly for individuals with disabilities.

## Lab objectives

You will be able to complete the following tasks:

- Task 1: Set Up Accessibility Insights for Web extension in Microsoft Edge
- Task 2: Verify the GitHub Copilot Chat extension and Clone the Accessible University GitHub Repo in VS Code

## Task 1: Set Up Accessibility Insights for Web extension in Microsoft Edge

1. Navigate to the **Accessibility Insights for Web** page using the provided URL below:
   
     ```
    https://accessibilityinsights.io/docs/web/overview/
     ```
     
1. From the Accessibility Insights for Web page, click on the **Download for Web** option.

   ![](../media/aut11.png)

1. Click the **+ Add to Microsoft Edge** button from the Download Accessibility Insights page.

   ![](../media/aut12.png)

1. Select the **Get** option.
   
   ![](../media/aut13.png)

1. A pop-up appears. Select the **Add extension** option from there. It will start downloading an extension in your web browser.

   ![](../media/aut14.png)

1.  Click on the **Extensions** **(1)** icon in the browser toolbar. From Accessibility Insights for Web, select the **(...)** **(2)** option and click on **Manage extension** **(3)**.
   
    ![](../media/aut15.png)

1. In the **Manage Extension** page, scroll down and click on the **Allow access to file URLs** checkbox.

   ![](../media/aut16.png)

## Task 2: Verify the GitHub Copilot Chat extension and Clone the Accessible University GitHub Repo in VS Code

1. Start **Visual Studio Code** from the desktop.

    ![Picture1](../media/vscode1.jpg)

     >**Note**: Ensure you don't open an already running instance of Visual Studio Code; instead, launch a new one from the desktop.

1. Click **File (1)** and then click on **New Window (2)**.

      ![](../media/new-window.png)

1. To verify the **GitHub Copilot Chat extension**, the following steps are to be performed within Visual Studio Code:
    - Click on the **Extensions (1)** icon in the activity bar present on the left side of the Visual Studio Code Window.
    - In the **"Search Extensions in Marketplace"** search box, type and search for the **GitHub Copilot Chat (2)** extension.
    - Select **GitHub Copilot Chat (3)** from the list of results that show up, and verify that **GitHub Copilot Chat** has been installed.
    - If not, click on the **Install (4)** button.

   ![](../media/ghc-chat-extension.png)

1. Once the installation is complete, in the top right next to the search bar, you will be able to see the icon for GitHub Copilot Chat, as shown below.

   ![](../media/E7T2S4-0807.png)

1. Skip to step 9. If you have already signed in to a GitHub Account in VS Code. If not, then follow steps 5 to 7.

1. Select the **Account** icon from bottom and click on **Sign in with GitHub**.

    ![Picture1](../media/clonerepo3.png)

1. Sign in with GitHub Credentials, and on the **Authorize GitHub for VS Code** page, click on the **Authorize Visual-Studio-Code.**

    ![Picture1](../media/clonerepo4.png)

1. If you get the pop-up, the site is trying to open Visual Studio Code, then click on **Open**. It will navigate back to the **Visual Studio**.

    ![Picture1](../media/clonerepo5.png)

1. If the files are already open, go to the toolbar, click on **Files**, and then select **Close Folder**.

   ![Picture1](../media/close-editor.png)

1. Open Command Prompt from the Windows search bar and navigate to the path `C:\Users\Azureuser`

    ![](../media/E7T2S10-0807.png)
    
1. Run the following command given below to clone the Accessible University GitHub repo.

    ```
   git clone https://github.com/CloudLabsAI-Azure/AU.git
    ```

    ![Picture1](../media/E7T2S11-0807.png)

1. Back on visual studio code switch to the **Explorer** in the upper left corner, select **Open Folder**.
   
   ![](../media/clonerepo1.png)

1. Select the **AU** folder you have cloned **(1)** and click **Select Folder (2)**.

   ![](../media/c30.png)

1. Select **Yes, I trust the authors**.

   ![](../media/trust-repo.png)

1. Once the folder is opened, select the `before.html` file.

   ![](../media/E7T2S15-0807.png)

1. Navigate to **File Explorer** and in search bar, type `C:\Users\azureuser\AU` then press **Enter**.

   ![](../media/c28.png)

1. It will  open the folder you have cloned. From there, double-click on the `before` HTML file. It will open in your web browser, where you have already added the **Accessibility Insights for Web** extension.

   ![](../media/c32.png)

   ![](../media/before1.png)

1. Now click on the **Extensions (1)** button from the browser toolbar, select **Accessibility Insights for Web (2)**, click on **OK** and then click on **FastPass (3)**. It will open in a pop-up window.

   - **FastPass**: [FastPass](https://accessibilityinsights.io/docs/web/getstarted/fastpass/) is a lightweight, two-step process that helps developers identify common, high-impact accessibility issues in less than five minutes.

   ![](../media/fastpass1.png)

   ![](../media/fastpass2.png)

1. In the new window for **Accessibility Insights for Web**, you will see the following three-step checklist for FastPass.

   - **Automated checks**: The tool automatically checks for compliance with dozens of accessibility requirements. 

   - **Tab stops**: The tool provides clear instructions, partial automation, and a visual helper that makes it easy to identify critical accessibility issues related to keyboard access, such as missing tab stops, keyboard traps, and incorrect tab order.

   - **Needs review**: The tool provides instances that need to be reviewed by a human to determine whether they pass or fail.

1. Expand the **color contrast** issue to check failure details.

   ![](../media/allissue.png)

1. Navigate back to Visual Studio Code, open the **before-menu.css (2)** file, which is located in the **styles (1)** folder.

   ![](../media/styles1.png)

1. In the **before-menu.css** file, find the CSS section addressing color contrast. Select the given code snippet, press **Ctrl + I** to bring up GitHub Copilot chat, input the prompt, and hit enter.

   ```
   Fix the colour contrast issue.
   ```

   ![](../media/colourcontrast0.png)

1. Review the suggestion from GitHub Copilot, which was generated based on the context provided, ensure that it meets your requirements, and click on the **Accept** option.

   ![](../media/colourcontrast1.png)

   >**Note**: It should be noted that the code suggestions offered by GitHub Copilot might not exactly match the screenshots shown within the lab guide. GitHub Copilot is an AI-powered tool that generates code based on context and patterns, and its suggestions can be influenced by various factors.

   >**Note:** If the suggestions do not appear, consider restarting Visual Studio Code and redoing the process.

1. Accepting this will modify the code.

   ![](../media/colourcontrast2.png)

1. **Save** the file by pressing **Ctrl + S**.

1. Now refresh your **Accessible University** page. 

   ![](../media/c33.png)

1. Click on the **Start over** button from the **Accessibility Insights for Web** page. You will now see a reduction in the error message.

   ![](../media/startover.png)

   ![](../media/reduction.png)

   >**Note**: Perform step 14 if the data wasn't reloaded.

1. Click on **html-has-lang** to review the error message in detail.

    ![](../media/langaccept2.png)

1. Navigate back to your VS Code, Open `before.html` file.

1. Select the `html` code, press **Ctrl + I** to access the GitHub Copilot chat, enter the given prompt, and click **Enter**.

   ```
   Add the html lang attribute
   ```

    ![](../media/langaccept0.png)

1. Review the suggestion from GitHub Copilot, which was generated based on the context provided, and ensure it meets your requirements. Click on the **Accept** option.

   ![](../media/langaccept.png)

1. Accepting this will modify the code.

   ![](../media/langaccept1.png)

1. **Save** the file by pressing **Ctrl + S**.

1. Now refresh your **Accessible University** page. 

   ![](../media/c33.png)

1. Click on the **Start over** button from  **Accessibility Insights for Web** page. You will now see a reduction in the error message.

   ![](../media/imgaltcoursela.png)

1. Now, expand the **image-alt** to view the error message.

1. Navigate back to your VS Code, Open `before.html` file.

1. In the **before.html** file, select the given code from line 79 to line 96, press **Ctrl + I** to open the GitHub Copilot chat, enter the given prompt, and press Enter.

   ```
   Fix the accessibility issue
   ```

   ![](../media/accessibility1.png)

1. Review the suggestion from GitHub Copilot, which was generated based on the context provided, ensure that it meets your requirements, and click on the **Accept** option.

   ![](../media/accessibilityaccept.png)

1. Accepting this will modify the code.

   ![](../media/accessibilityfinal.png) 

1. **Save** the file by pressing **Ctrl + S**.

1. Now refresh your **Accessible University** page. Click on the **Start over** button from the **Accessibility Insights for Web** page. You will now see a reduction in the error message.

   ![](../media/startover.png)

   ![](../media/reduction1.png)

1. Now, expand the **label** to check the error message in detail.

1. Navigate back to your VS Code, Open `before.html` file.

1. In the **before.html** file, select the given code from line 199 to line 212 and press **Ctrl + I** to access the GitHub Copilot chat. Provide the given prompt and press Enter.

   ```
   Add a label to the selected code
   ```

   ![](../media/labelaccept.png)

1. Review the suggestion from GitHub Copilot, which was generated based on the context provided, ensure that it meets your requirements, and click on the **Accept** option.

   ![](../media/labelaccept1.png) 

1. Accepting this will modify the code.

   ![](../media/labelaccept2.png) 

1. **Save** the file by **Ctrl + S**.

1. Refresh your **Accessible University** page. Click on the **Start over** button from the  **Accessibility Insights for Web** page. You will now see a reduction in the error message.

1. Expand the **link-in-text-block** to view the error details.

   ![](../media/linktxt.png)

1. Navigate back to your VS Code.

1. In the **before.html** file, select the given code from line 125 to line 129, and press **Ctrl + I** to access the GitHub Copilot chat. Provide the given prompt and press Enter.

   ```
   Fix for all: one of the following issues: improve link color contrast to at least 3:1 or add styling (e.g., underline) to distinguish it from surrounding text.
   ```

   ![](../media/linkaccept0.png)

1. Review the suggestion from GitHub Copilot, which was generated based on the context provided, and ensure that it meets your requirements. click on **Enter**.

   ![](../media/linkaccept.png)

1. Accepting this will modify the code.

   ![](../media/linkaccept2.png) 

1. **Save** the file by pressing **Ctrl + S**.

1. Refresh your **Accessible University** page. Click on the **Start over** button from the **Accessibility Insights for Web** page. You will notice that there is no issue left.

   ![](../media/allresolve.png)

### Summary

In this exercise, you successfully integrated Accessibility Insights for Web into Microsoft Edge and used it to identify accessibility issues on the AU homepage. By leveraging GitHub Copilot Chat in Visual Studio Code, you generated and implemented code solutions to fix these issues. This process ensured the website met accessibility standards, enhancing usability and inclusivity for all users, including those with disabilities. Refer to the link for more information about [Accessible University](https://www.washington.edu/accesscomputing/AU/).

## You have successfully completed the lab. Click on **Next >>** to proceed with the next exercise.
