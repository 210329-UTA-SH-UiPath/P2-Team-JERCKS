# Job Grabber
  
## Project Description
Job Grabber is our automation project that is centered around creating an attended robot that will assist a user with aggregating job postings found across online different job boards. Taking only one input from the user, the robot will then proceed to go to work and quickly compile a list of jobs in an Excel document. This list will contain a summary of all the information you might want to know about each job posting as well as a link to the actual posting if you decide to apply.
 
## Technologies Used
- UiPath Studio
- Git/GitHub

## Features

Ready features within project
* Aggregates job listings from different websites (Indeed, Monster, ZipRecruiter)
* Places all job listings in a single Excel file in the project's folder
* Sends an email to the user with the Excel file attached

Improvements for future iterations
* Iterate through multiple pages of jobs on each website rather just the first page.
* Implement more ways to filter out data (eg., desired skills, reviews, etc.)

## Installation
To install:
- In command line, use "git clone" this repository to create a repository on your machine.
- Download UiPath Studio from UiPath's website (Community edition should suffice)
- Within UiPath Studio, select the open project in the home screen and select the files for this project.

## Usage
When the project is opened in UiPath Studio, the user should navigate to the Main.xaml file. In the top task bar, click "Run File" and the automation should begin executing. The user will then be prompted to enter a couple fields including, job search keywords, expected skills to have, and the miminum pay expected. Once these have all been entered, the automation will then take control over your screen. During that time, please do not interact with the screen as it could mess with the automation's process. In a normal environment, it should take only around a minute to complete. The automation will then provide a message box telling you it has complete and you can check your email to find the Excel file.

## Contributors 
Eduardo Reyes, Kirby Chan, Joe Stalnaker

## Licenses
[MIT License](https://github.com/210329-UTA-SH-UiPath/P2_Team_JERCKS/blob/master/LICENSE)

## Flow Chart

![Flow Chart Diagram](https://raw.githubusercontent.com/210329-UTA-SH-UiPath/training-code/main/P2%20Proposals/EduardoFlowChart.png)
