## PigyBank -Reporting and Transaction (By Isreal Ogbu, Fagbemi Ayomide)

This is a project that is mainly built for the #APISecurityHackathon. We are also looking forward to building more sub applications on it.

The project for the hackathon challenge will be mainly focussed on Authentication, Authorization, Reporting customer feedback (Notification, Enquiry) and Investment section(APIs).
For the sake of the hackathon, we will not be using any third party databse. We will be taking advantage of the
Database provided by Django (Sqlite).
***

## Tools to ensure the solution runs effectively
***

Ensure you have `Vscode` or `Pycharm` installed on your machine.

Also ensure you have `pip` installed. This is a package installer for python.

create a subdirectory for the project, and move into the directory either on pycharm or vscode.

Create a virtual environment by running :
`python -m venv venv`

Activate your virtual environment by running the command:
For windows: `venv/scripts/activate`
For Mac : `source venv/bin/activate`

Once the above  is installed and done, You set for the project.
***
## How to Install and run pigybank project.
***
To run Pigybank project on your machine:
1. Initialize your directory with git by running : `git init`
2. create a branch for the project by running : `git branch -m <you branch name>`. This can be optional if you want solve some issues 
3. Clone this repository by running : `git clone https://github.com/Isreal-ogbu/pigybank`
4. To install packages and dependencies, run: `pip install -r requirements.txt`

Before running projects, There are some environmental variables that you will need to set.
create a file, call it `.env`. Input the below with appropriate values:

1. `SECRET_KEY`
2. `TREBLLE_API_KEY`
3. `TREBLLE_PROJECT_ID`

**Note: There are some sensitive variable that are not provided in this repo as a result of privacy. We intended depricating it
  so it does not affect the application or make the code break.
***

