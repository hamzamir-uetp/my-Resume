# My First Cloud Computing Project: An Online Resume  

## Overview  
I have converted my professional resume into a static website and deployed it using Microsoft Azure's Static Web Apps service. The code is hosted on GitHub and the entire deployment process is automated using GitHub Actions.  

## Technologies Used
 # 1. HTML:
      For creating the structure and style of the CV website.
 # 3. GitHub:
      To host the project code and manage version control.
 # 4. Azure Static Web Apps:
      To deploy the website and make it accessible on the internet.

## Project Steps
 # 1. Azure Account Creation:
     Created an Azure account using the Azure for Students offer, which provided free credits to get started.

 # 2. CV Conversion:
     I converted my CV from a PDF document into a web page using index.html.

 # 3. GitHub Repository:
     I created a new public GitHub repository named "my-Resume" to store my project files.

 # 4. Deployment to Azure:
     I used the Azure Static Web Apps service to deploy the website. I connected the service to my GitHub repository, which automatically created a GitHub Actions workflow to handle the continuous deployment.

## Challenges 
I initially encountered an error where the build process failed because my simple HTML/CSS site did not require a build step. I fixed this by reconfiguring the app with the correct output location or by editing the GitHub Actions workflow file to bypass the build process.

## Live Demo  
👉 [View My Resume](https://red-sand-0e041b500.2.azurestaticapps.net)  
