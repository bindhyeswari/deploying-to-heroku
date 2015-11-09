#How to Deploy a NodeJS Application to Heroku

 - Install the Heroku toolbelt (give hyperlinks)
 - Add public key to Heroku accounts (give hyperlink) to enable SSH
 - Create a NodeJS application
 - Create a .gitignore and ignore files --> 
 - Create a file named Procfile in the project root
 - Append the line to the Procfile ```web: node bin/www```
 - Initiate git repository and commit files
 - Create a heroku application by typing ```heroku create appname```
 - ```git push heroku master``` to deploy to heroku

#References

 - [Markdown](https://daringfireball.net/projects/markdown/syntax)

#Steps On Launching Heroku Apps

##Installing Heroku ToolBelt
    
- First you need to download Heroku Toolbelt to start using Heroku.
- [Heroku Toolbelt Link](https://toolbelt.heroku.com/)
- Download Heroku Tool Belt.
- After downloading, install Heroku via terminal by typing "heroku".... This process might take a few minutes.
- After installing, check to see Heroku has been installed by typing "heroku --version"... This will show you the latest/recent version of heroku.

##Generating SSH key
 - Here is the link for step-by-step process on generating a SSH key for heroku.
 - [Link for Reference](https://devcenter.heroku.com/articles/keys)
 - To get SSH key you want to type "ssh-keygen -t rsa" to the terminal.
 - Press enter to save the key into default path
 - Set up a password so no one can have access to your SSH keys
 - Then you want to add the key(s) to heroku by typing "heroku keys: add".
 - This will add the SSH key to Heroku. If you see more than one make sure you pick the right SSH key value.