# Getting a list of repos from a GitHub user
This bash function gets a list of all repos for a GitHub user, or returns more detailed information on a user specified GitHub repo.

## Getting started
Before you can use this function you need to copy it into your ~/.bash_profile, replace the "USERNAME" with your GitHub username, and open a new terminal window or source ~/.bash_profile to refresh the opened terminal window. 

Since this function uses jq to parse the JSON, you will also need to download jq if it's not already enabled on your computer. You can download jq [here](https://stedolan.github.io/jq) or use [homebrew](http://brew.sh) to install jq 1.5 with `brew install jq`. 

There are two options. You can get a simple list of all repos for a user responding with the repos name and description. Or, input a specific repo name and get a more detailed list of information regarding that one specific repo.

Addtional fields can be returned by adding them to the list of objects jq will query.

## Additions
Adding an option to view all issues assoicated with a repo and it's lables could be benefical. Perhaps a future enchancement. 
