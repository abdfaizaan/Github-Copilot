# Introduction to GitHub Copilot

### Estimated Duration: 10 minutes

GitHub Copilot is the world's first at-scale AI developer tool that can help you write code faster with less work. GitHub Copilot uses comments and code context to instantly suggest specific lines of code and the entire functions.

Research has found GitHub Copilot helps developers code faster, focus on solving bigger problems, stay in the flow longer, and feel more fulfilled with their work.

Powered by OpenAI Codex and GitHub Copilot's generative, pre-trained language model was created by OpenAI. An extension is available for Visual Studio Code, Visual Studio, Neovim, and the JetBrains suite of integrated development environments (IDEs).

## Prerequisites

 - Basic understanding of GitHub fundamentals
 - A GitHub Enterprise Cloud administrator account

## Github Copilot for Individuals

GitHub Copilot is an AI-powered coding assistant developed by GitHub, designed to help individual developers by providing intelligent code suggestions, automating repetitive tasks, and enhancing productivity during software development. It leverages machine learning models trained on vast repositories of code to generate code snippets, and complete functions, and offer contextual suggestions based on the developer's input and coding patterns. Copilot supports various programming languages and adapts to individual coding styles, making it a valuable tool for accelerating coding tasks, exploring new techniques, and improving code quality.

Ways in which the data in GitHub Copilot Individual can be used and shared :

- **Enhancing GitHub Copilot**: The data collected is utilized to improve GitHub Copilot by evaluating different strategies for processing and predicting suggestions that users may find valuable.
- **Developing related developer products and services**: The insights gained from the data help in the development and improvement of other developer tools and services offered by GitHub and Microsoft.
- **Detecting abuse and policy violations**: The data is examined to investigate and identify any potential misuse or violation of the Acceptable Use Policies associated with GitHub Copilot.

## GitHub Copilot for Business

GitHub Copilot is available through GitHub personal accounts with GitHub Copilot for Individuals or through organization or enterprise accounts with GitHub Copilot for Business.

With Copilot for Business, you can manage access to GitHub Copilot for organizations within your enterprise. Once you grant an organization access to GitHub Copilot, the organization's administrators can grant access to individuals and teams.

With GitHub Copilot for Business, GitHub Copilot is open to every developer, team, organization, and enterprise.

Focused on making organizations more productive, secure, and fulfilled, GitHub Copilot for Business allows developers to code faster and allows them to focus on more satisfying work.

Here are some features you can expect from Copilot for Business:

 - A robust AI model: New modeling algorithms improve the quality of code suggestions.
 - AI-based security vulnerability filtering: GitHub Copilot automatically blocks common insecure code suggestions by targeting issues such as hardcoded credentials, SQL injections, and path injections.
 - VPN proxy support: GitHub Copilot works with VPNs, including with self-signed certificates, so developers can use it in any working environment.
 - Simple sign-up: Regardless of whether a business does not use the GitHub service for its source code, it can easily buy Copilot for Business licenses online and assign seats.

## GitHub Copilot for Enterprise

GitHub Copilot Enterprise is a Copilot plan available for enterprises that use GitHub Enterprise Cloud. It provides AI features to enhance your experience on GitHub.com, such as the ability to chat with Copilot in the browser and reference context for Copilot from across your project repositories.

Enterprise owners can allow some or all organizations in the enterprise to access GitHub Copilot. If an organization has access to Copilot, owners of the organization can assign Copilot Enterprise seats to some or all members of the organization.

### GitHub Copilot Enterprise includes the following features, available to all users who are assigned a GitHub Copilot Enterprise seat:

- **GitHub Copilot in your IDE**: GitHub Copilot is an AI tool that offers autocomplete-style suggestions in your IDE.
- **GitHub Copilot Chat in your IDE**: GitHub Copilot Chat in your IDE is a chat interface that lets you ask and receive answers to coding-related questions within supported IDEs.
- **GitHub Copilot in the CLI**: GitHub Copilot in the CLI provides a chat-like interface in the terminal that allows you to ask questions about the command line. You can ask GitHub Copilot to provide either command suggestions or explanations of given commands.
- **GitHub Copilot Chat in GitHub.com**: GitHub Copilot Chat in GitHub.com is a chat interface that lets you ask and receive answers to coding-related questions within GitHub.com.
- **Copilot pull request summaries**: Copilot pull request summaries is an AI-powered feature that allows you to create a summary of the changes that were made in a pull request, which files they impact, and what a reviewer should focus on when they conduct their review.

### Understanding the differences between Copilot for Individuals, Business, and Enterprise


|                                                            | GitHub Copilot for Individuals |GitHub Copilot for Business | GitHub Copilot Enterprise |
| ---------------------------------------------------------- | --------------------------- | ------------------------------- | ------------- |
| Agent Mode                         | Up to 50 per month	   |    Unlimited with GPT-4o                   |    Unlimited with GPT-4o |
| Code review                          |✕	   |      ✓                 |    ✓  |
| Copilot Extensions                   |      ✓                 |       ✓                 |    ✓  |
| Inline chat                  |      ✓                 |       ✓                 |    ✓  |
| Generate tests, docs, and more with slash commands                  |      ✓                 |       ✓                 |    ✓  |
| Summaries for pull requests, issues, and discussions                        |✕	   |      ✓                 |    ✓  |
| Attach knowledge bases to chat for organizational context  |             ✕	             |   ✕	 | ✕	   |
| Slash commands and context variables                  |      ✓                 |       ✓                 |    ✓  |
| Context-aware coding support and explanations                  |      ✓                 |       ✓                 |    ✓  |
| Debugging and security remediation assistance                  |      ✓                 |       ✓                 |    ✓  |
| Copilot Chat, agent mode, code review, and Copilot Extensions use premium requests, with usage varying by model                         | Up to 50 per month	   |   Up to 300 per month                  |    Up to 300 per month  |


### GitHub Copilot for Business Use Cases

GitHub Copilot improves developer productivity and happiness, reduces disruptions, improves flow, and increases the amount of time a developer spends doing satisfying work.

 - Developers code faster.
 - Developers stay in the flow longer.

### How to get started with GitHub Copilot for Business?

Using GitHub Copilot for Business in your enterprise: You must first establish a policy for using GitHub Copilot for Business in your enterprise. Once GitHub Copilot for Business is enabled at the enterprise level, you can configure GitHub Copilot settings for each organization in your enterprise.

### Enabling GitHub Copilot Enterprise

To enable users to use Copilot Enterprise features, your GitHub Enterprise Cloud enterprise must have a subscription to Copilot Enterprise.

Access to Copilot is determined at the enterprise and organization levels:

- Enterprise owners can allow some or all of the organizations in the enterprise to access Copilot.
- Owners of organizations that have been granted access to Copilot can assign GitHub Copilot Enterprise seats to some or all members of their organization. 

When access to Copilot has been enabled, features such as the ability to use Copilot on GitHub.com can be configured. Features are enabled or disabled at the enterprise or organization level:

- Enterprise owners can set Copilot features to be enabled or disabled for all organizations in the enterprise that have access to Copilot. Alternatively, they can allow each organization to set its policy for each feature.
- If the enterprise owner has permitted it, organization owners can enable or disable Copilot features for their organization.

### Summary

We learned about GitHub Copilot, an AI-powered coding assistant that integrates with IDEs to provide real-time code suggestions, explanations, and refactoring support. We explored its Individual, Business, and Enterprise plans, understanding their features, security enhancements, and management options to improve developer productivity and streamline coding workflows across organizations.

Click on **Next** from the bottom right to start with the lab.
