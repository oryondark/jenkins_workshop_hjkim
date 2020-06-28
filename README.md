# jenkins_workshop_hjkim
Hello, My name is Hyunjun Kim<br>
You can call me 'Jey'!
<br>
<br>
## Workflow
1. Launch to EC2 instance (t2.micro for amzninstance type)
2. install jenkins server on EC2
3. Let it clone repository to your notebook
4. setup webhook your github cloned repository
5. setup git for pushed event in jenkins server
6. change autor from your **pakcage.json**
7. add content of build_script to **build** in jenkins configuration
8. add `jenkins ALL=(ALL) NOPASSWD: ALL` to **/etc/sudoers**
9. `git add . & git commit -m 'update' & git push -u origin master`

