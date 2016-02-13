# Getting a list of repos from a GitHub user
This bash function gets a list of all repos for a GitHub user. I use jq to parse the JSON by only returning each repo's name and description. 

## Getting started
Before you can use this function you need to copy it into your ~/.bash_profile, replace the "USERNAME" with your GitHub username and open a new terminal window or source ~/.bash_profile to refresh the opened terminal window. 

Since this function uses jq to parse the JSON you will also need to download jq if it's not already enabled on your computer. You can download jq [here](https://stedolan.github.io/jq) or use [homebrew](http://brew.sh) to install jq 1.5 with `brew install jq`. 
