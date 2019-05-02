#To do 

entry point script to modified ownership for /var/www/ | /var/www/*

Because whith:

 docker-compose up -d --build image 

we switch to user but volume is set to root which will cause error
on editing files. Composer will not have writes to run it because 
we will run it as www-data and ownership is set it as root.

I wanted to gain options where script run command to create docker
machine with name set it at the begining. And I use .env file to read
app name to use it as mouting point in docker-compsoe.yml



Idea: Maybe use verions 3 // checking for bugs on volumes mouting.








run command to can use script:

chmod u+x build-project		//from directory

./build-project -c test		//tested on Fedora 29

[PL]
$() -> zapis do zmiennej aby ja wykonac
${} -> wykonananie wyniku i podstawienie do zmiennej 
