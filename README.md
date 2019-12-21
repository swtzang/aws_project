# aws_project
# aws 
## How to save your codings in AWS rstudio to github?

Now in rstudio, under the Tools menu click Shell… to open on a command prompt. Run the following three commands to introduce yourself to git and turn on the credential helper to store your GitHub password so you don’t have to type it every time. Be sure to substitute your name and the email address associated with your GitHub account.

git config --global user.name 'Your Name'

git config --global user.email 'your@email.com'

git config --global credential.helper 'cache --timeout=10000000'

Reference: 
http://strimas.com/r/rstudio-cloud-2/
