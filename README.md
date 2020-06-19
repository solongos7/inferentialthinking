# MS Learn Foundations of DataScience

This repository contains some labs to help you get started. These labs are designed to introduce you to some of the core concepts in DataScience, and the DataScience Python Library. For the Learning Path Foundation of Data Science https://docs.microsoft.com/en-us/learn/paths/foundations-data-science/

The labs are provided as notebooks that contain explanations of key DataScience principals and code.

[![Open in Visual Studio Online](https://img.shields.io/endpoint?style=social&url=https%3A%2F%2Faka.ms%2Fvso-badge)](https://online.visualstudio.com/environments/new?name=MSLearn-DataScience&repo=MicrosoftDocs/inferentialthinking)

## Manually creating a VS Online Container

To complete the labs, you'll need the following:

- A Microsoft Azure subscription. If you don't already have one, you can sign up for a free trial at <a href ='https://azure.microsoft.com' target='_blank'>https://azure.microsoft.com</a> or a Student Subscription at <a href ='https://aks.ms/azureforstudents' target='_blank'>https://aka.ms/azureforstudents</a>.
- A Visual Studio Online environment. This provides a hosted instance of Visual Studio Code, in which you'll be able to run the notebooks for the lab exercises. To set up this environment:
    1. Browse to <a href ='https://online.visualstudio.com' target='_blank'>https://online.visualstudio.com</a>
    2. Click **Get Started**.
    3. Sign in using the Microsoft account associated with your Azure subscription.
    4. Click **Create environment**. If you don't already have a Visual Studio Online plan, create one. This is used to track resource utlization by your Visual Studio Online environments. Then create an environment with the following settings:
        - **Environment Name**: *A name for your environment - for example, **MSLearn-Datascience**.*
        - **Git Repository**: MicrosoftDocs/inferentialthinking
        - **Instance Type**: Standard (Linux) 4 cores, 8GB RAM
        - **Suspend idle environment after**: 120 minutes
    5. Wait for the environment to be created, and then click **Connect** to connect to it. This will open a browser-based instance of Visual Studio Code.
    6. Wait for a minute or so while the environment is set up for you. It might look like nothing is happening, but in the background we are installing some extensions that you will use in the labs. You'll see the following things happen:
        - The files in this repo will appear in the pane on the left.
        - The color scheme will change to a light background with dark text.
        - Eventually, a new file named REFRESH NOW will appear in the pane on the left. This is your indication that everything has been installed.
    7. After the REFRESH NOW file has appeared, refresh the web page to ensure all of the extensions are loaded and you're ready to start.
    8. Note the numbered *.ipynb* files in the **Explorer** pane - these contain the lab exercises.

> **Tip**: you can change the color scheme back to a dark background if you prefer - just click the **&#9881;** icon at the bottom left and select a new **Color Theme**.

## Labs

After you've completed the setup steps above, you can use your Visual Studio Online environment to complete the labs.


> **Note**: Labs that involve running code include all of the code you'll need - you'll just need to copy and paste a few values and run the code that is provided, so don't worry if you're not a programmer! We've used Python code in the labs, because that can be runs interactively in the notebooks themselves.
