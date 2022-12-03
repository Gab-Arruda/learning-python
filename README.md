All the python files here were made when I was studying python for the first time using this tutorial https://www.youtube.com/playlist?list=PLvE-ZAFRgX8hnECDn1v9HNTI71veL3oW0

To make a commit I need to use the following commands in git bash:
+ eval "$(ssh-agent -s)"
+ ssh-add ~/.ssh/id_rsa
+ To check if the ssh was indeed added use  ssh-add -l
+ To test connection run ssh -vT git@github.com
+ git push

In powershell(the agent is supposed to start automatically on OS boot):
+ ssh-add C:\Users\cebol\.ssh\id_rsa
+ To test connection run ssh -vT git@github.com
+ git push