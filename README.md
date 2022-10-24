# nlp2022
This is the repository for the Cornell Digital Humanities Club's NLP subteam's 2022-23 project

## Setup and Installation

### Basic Tools
To set up the local environment for the project, you'll need a functional
knowledge of how to use the terminal (sometimes referred to as the command line)
as well as an understanding of git and GitHub.

Here are some helpful resources for the above:
* Terminal/Command Line
    - [Command Line Crash Course by Mozilla](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line)
    - [Basic Commands (MacOS)](https://medium.com/macoclock/10-essential-mac-terminal-commands-9a100805918c)
    - [Basic Commands (Windows)](http://ifoundthemeaningoflife.com/learntocode/cmd101win)
* Git
    - [Simple Git Guide](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)
    - [Atlassian's Git Guide](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)
    - [Intro to GitHub](https://docs.github.com/en/get-started/quickstart/hello-world)

### Local Environment Setup
#### Cloning the Repository
Using the terminal, navigate into the folder that you 
want to contain the project.

Then, run the following command:
```
git clone https://github.com/ak2243/nlp2022.git
```

*Note: Make sure you have been added as a collaborator*

#### Install dependencies
For this step, make sure that you have Python installed.

*The next step is recommended but not required.*

Create a virtual environment using the following command:
```
python3 -m venv venv
```

This makes it so that dependencies and packages are installed
within the project folder instead of cluttering your computer.

Now, you can run the following command to install the project dependencies (including jupyter notebook):

```
pip3 install -r requirements.txt
```

#### Usage
If you made a virtual environment, you should run the following before each time you work on the project.

Windows:
```
venv\Scripts\activate.bat
```

MacOS:
```
source venv/bin/activate
```

You should then see a (venv) before your terminal prompt, 
indicating that you are in the virtual python environment.

You can exit the virtual environment by simply running `deactivate` in your terminal.

When you're in the virtual environment (if applicable), 
run `jupyter notebook` to start working.