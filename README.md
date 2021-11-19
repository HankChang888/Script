
# 1.How to create $PRJ valible in my ubuntu?
if your parameter has $ symbol,that is the valible.  
1.1 Export $PRJ ENV.valible  
export PRJ=$PRJ"/home/hank/myproject" 
then check the $PRJ is valid  
echo $PRJ  
1.2 Clearn $PRJ configuration  
exprot PRJ=""  
then check the $PRJ is valid  
echo $PRJ  
1.3 If you want to save the $PRJ valible,you can write into etc/profile  
vi /etc/profile  
then put on the top  
export PRJ=$PRJ"/home/hank/myproject" 
