# 1.	How do you download files from a GitHub repository?<br>
### Change the directory to the location where the repository will be cloned to<br>
 
![image](https://user-images.githubusercontent.com/90805082/167743231-77368bcf-4cca-43f8-b811-f799ad91003f.png)<br>
### Use the "git clone <URL>" command to clone the repository then hit Enter<br>
![image](https://user-images.githubusercontent.com/90805082/167743378-725e8eb1-eaa6-4626-906f-4833784ec335.png)<br>
### The benefit of using this method is that the files are automatically unzipped when downloaded.<br><br>

  
  
  
  
  
  
# 2.	How do you move files on your local machine?<br>
### The "mv" command moves the file or folder from its old location and puts it in the new location<br>
## Examples of "mv" command
% mv ~/Desktop/test_repos/code-compare/code-compare/index-jg.html ~/Desktop/test_repos/code-compare/code-compare/group5/index-jg.html<br>
![image](https://user-images.githubusercontent.com/90805082/167744191-0fd8b75a-8c35-46c9-9e6c-c01276b45d6a.png)

### You can also change the name of the file as it’s moved:<br><br>
mv ~/Desktop/test_repos/code-compare/code-compare/group5/index-jg.html ~/Desktop/test_repos/code-compare/code-compare/group5/newName.html
![image](https://user-images.githubusercontent.com/90805082/167744335-a25bbaf7-5238-4db2-8b5c-7639bd451a8b.png)

<br><br>

  
  
  
  
# 3.	How do you edit files on your local machine?<br>
### To edit a file on a local machine you can use an editor like nano
 ![image](https://user-images.githubusercontent.com/90805082/167745435-54788586-e9f9-4c3e-8d66-14aeb01082e4.png)
 ![image](https://user-images.githubusercontent.com/90805082/167745515-636e1076-0dd2-4804-b5cc-d922b25dc007.png)
### Use control+X on your keyboard to exit and save the file<br>
### To verify that your changes saved to the file use the "cat" command
![image](https://user-images.githubusercontent.com/90805082/167745740-2158fd33-3dca-4d47-9bb1-b501686b9bc3.png)
<br><br>

  
  
  
# 4.	How do you test code locally to verify that it works?<br>
### To test your code locally use the "open" command followed by the name of the file.
![image](https://user-images.githubusercontent.com/90805082/167746060-f98c27dc-a402-4799-89b3-f5b0f7fe7838.png)

### Editing with nano and testing locally<br>
![image](https://user-images.githubusercontent.com/90805082/167745957-250ef293-1fbe-4b30-a38a-966970b51583.png)

<br><br>

  
  
# 5.	How do you merge your changes back to the main project on GitHub?<br>
### First step to merging is using the "git init" command, but since our repository already exists we can skip this step<br>
### Use “git add” command followed by the file name to stage the files before pushing
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/90805082/167746210-ad5f69d5-68ac-47df-ad23-c741655e5e8d.png">

### Use “git commit” to commit the changes locally before using “git push”. Add a message/comment by adding<br>“-m” this helps identify any changes that were made.<br>
<img width="468" alt="image" src="https://user-images.githubusercontent.com/90805082/167746246-27b8b477-1132-485e-8e17-2298b9ac949a.png">
  
### Use “git push” followed by the repository URL to push any changes on the files being merged.
<img width="468" alt="image" src="https://user-images.githubusercontent.com/90805082/167746280-4fc740a9-f79d-473d-a198-9d25c58c5f53.png">

### Final step is to check for successful merge back on the master in GitHub
![image](https://user-images.githubusercontent.com/90805082/167748311-682ec203-e79a-41be-8867-a0a218249401.png)

 
