# people10.docker.redvulture.github.io
Instructions -  The code challenge consists of 3 challenges.  You have to attempt 2 out of which Dockers challenge is mandatory. Also check the Readme file for detailed instructions.


Thanks for taking time to speak with me regarding the DevOps Lead role. 
As discussed, please find the code challenge (attached) to be completed to 
proceed to the next round 

Time Estimate - The entire code challenge won't take you more than 3 hours to complete

Instructions - 
The code challenge consists of 3 challenges. 
You have to attempt 2 out of which Dockers challenge is mandatory.
Also check the Readme file for detailed instructions.
On completion, 
please upload the code into a GitHub Repository-> Make the link Public-> Share the link with me 
80% of the evaluation process gets done with this code challenge and just a 
formal discussion with the hiring manager would be pending. 


Devops-code-challenge-2016
Royal C. Jackson Jr.
Will Submit all Three Challenges
People10 Technologies\devops-code-challenge

Github Public Repo
people10.docker.redvulture.github.io
URL: https://github.com/GitHubShark39/people10.docker.redvulture.github.io/blob/master/README.md


## Introduction

This project is designed as a quick exercise to gauge a candidate's
understanding of general automation and systems knowledge.

## Terms & Conditions

Challenges are time restricted based on which challenges you have accepted or
have been asked to complete.

- 2 days for candidates only doing one challenge
- 5 days for candidates doing all 3 challenges

*Note: Use of third-party plugins other than those defined within project
is allowed. But please take into account to demonstrate your strengths and
not leave your experience and capabilities to question. No commercial or
proprietary plug-ins are allowed.*

Build this project out in the most appropriate way possible.  Treat it as a
"real-world component" that will be added into our system.  Feel free to
restructure/enhance the project as you see fit. However, you must follow the
restrictions described above. Lastly, solutions should be easily built on
a standard linux, osx machine or browser.

## The Challenges

### Configuration challenge

Automate the process of provisioning a configuration file onto multiple hosts
in multiple environments. You can use any technique you see fit (shell script,
configuration management tool, etc.). 

Deploy the file to /etc on the remote host.
Set the mode to 0644 and root:users ownership. 
You will need to dynamically set the value for "databaseServer" depending on 
what environment you are deploying to (development or production).

app-config.conf

The configuration managment tool used was Ansible and is included
in this github repository.

### Docker Challenge

Create a docker container based on tomcat that will run pebble 
(http://pebble.sourceforge.net/)

The container should download the latest stable build of pebble.
The container should set the credentials in tomcat-users.xml to admin/admin.
The Pebble war should run under the context people10.docker.redvulture.github.io/pebble-2.6.4/

Result should be a zip file with the DockerFile used as well as any supporting
files needed to run the container. 


### Automation Challenge

Devise a plan to automate the installation of an RPM onto RHEL/CENTOS host(s).
The solution should allow for the number of hosts that the RPM will install to 
easily scale. You will need to create a spec file/rpm from the tar below. This
will be a simple apache website. The goal is to run the automation and be able
to browse to http://localhost to see the site.

Result should be the spec file and rpm used as well as the framework used for
automation. For the automation framework, you can provide a synopsis of how
the work would be completed or applicable configs from any popular 
configuration tool (Puppet, Ansible, Chef, etc.)

automation.tar.gz

## Good Luck!
