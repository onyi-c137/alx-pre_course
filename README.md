0x01-git  README.md                                                                                                                   
root@7170424fc4a9:~/alx-pre_course# git pull                                                                                          
Already up to date.                                                                                                                   
root@7170424fc4a9:~/alx-pre_course# cat README.md                                                                                     
My updated readme                                                                                                                     
root@7170424fc4a9:~/alx-pre_course# cd 0x01-git                                                                                       
root@7170424fc4a9:~/alx-pre_course/0x01-git# ls                                                                                       
bash  c  js  README.md                                                                                                                
root@7170424fc4a9:~/alx-pre_course/0x01-git# touch up_to_date                                                                         
root@7170424fc4a9:~/alx-pre_course/0x01-git# git add up_to_date                                                                       
root@7170424fc4a9:~/alx-pre_course/0x01-git# echo "git pull" > up_to_date                                                             
root@7170424fc4a9:~/alx-pre_course/0x01-git# cd ..                                                                                    
root@7170424fc4a9:~/alx-pre_course# git commit -m 'How to be up to date in git'                                                       
                                                                                                                                      
*** Please tell me who you are.                                                                                                       
                                                                                                                                      
Run                                                                                                                                   
                                                                                                                                      
  git config --global user.email "you@example.com"                                                                                    
  git config --global user.name "Your Name"                                                                                           
                                                                                                                                      
to set your account's default identity.                                                                                               
Omit --global to set the identity only in this repository.                                                                            
                                                                                                                                      
fatal: unable to auto-detect email address (got 'root@7170424fc4a9.(none)')                                                           
root@7170424fc4a9:~/alx-pre_course# git config --global user.email "onyangojeff2017@gmail.com"                                        
root@7170424fc4a9:~/alx-pre_course# git config --global user.name "Japh"                                                              
root@7170424fc4a9:~/alx-pre_course# git commit -m 'How to be up to date in git'                                                       
[master 1cad16a] How to be up to date in git                                                                                          
 1 file changed, 0 insertions(+), 0 deletions(-)                                                                                      
 create mode 100644 0x01-git/up_to_date                                                                                               
root@7170424fc4a9:~/alx-pre_course# git push                                                                                          
Enumerating objects: 5, done.                                                                                                         
Counting objects: 100% (5/5), done.                                                                                                   
Delta compression using up to 2 threads                                                                                               
Compressing objects: 100% (3/3), done.                                                                                                
Writing objects: 100% (3/3), 356 bytes | 356.00 KiB/s, done.                                                                          
Total 3 (delta 1), reused 0 (delta 0)                                                                                                 
remote: Resolving deltas: 100% (1/1), completed with 1 local object.                                                                  
To https://github.com/onyi-c137/alx-pre_course.git                                                                                    
   1cecd76..1cad16a  master -> master                                                                                                 

