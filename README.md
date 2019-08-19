# test
test1
```
IF I have github work and want to copy to gitee:
git remote add gitee https://gitee.com/zakigo/test.git
git push -u gitee master

IF I dont want to print two times of git push:
I CAN:
vim .git/config
add:
 12 [remote "all"]
 13     url=https://gitee.com/zakigo/test.git
 14     url=https://github.com/zakigo/test.git
then 
 git push all

IF I dont want to input usrname and password everytime
I CAN:
git config --global credential.helper store

IF I want to conmit I CAN:
git push all
or git push -u all -f
```
