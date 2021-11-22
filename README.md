This project is impilimented using php for banckend and front end is developed using HTML CSS and java scripit.
Steps needed to follow to run the code
1.download the source code into the local computer
2.unzip the file
3.Now first install xammp server on your local computer
4.open php controll panel start php server and mysql
5.open myphpadmin page and create database name with a name "urlshortener" and import sql file present in url folder your ready to do now
6.open browser and type "localhost/url"
Now about project
As i said project is been developed using php,index.php has the main logic of project. According to the problem statement provided i came witha soultion to shortern the web links by making the database which contains two three columns mainly one is orginallink,shorternlink and no of hits.main logic goes around that when ever a a new link is enter in the brower i'll take address check in my database is the shortren urls is present or not if a url is present i retive the data from the data base of orginal link which was previously stored in database ,Now before rediricting to the webpage first i will increment the count of no of hits of the url and then redircet to the webpage.
Now coming to part where to create a short url,provided a web interface where their is a input feild,user can enter a url,if entered url is vaild which i checked using regural expressions.and user clicks on gentrate file,a random integers of lenght of 5 are greated and add with local host and inserted into the database with orginallink and shorternlink and no of hits ans zero. Now a displayed a pop-up menu where shortren url is displayed with edit option if user edits the url and click's the save button the newly edit url is checks in datadbase is the link is avaliable new link is updateed in database or else a error message is displayed to retry to shortren url
Apart from these a new feature is also provide while displaying the list of urls that is delete feature if a user want to delete a url from the data base he can direct press delete button present beside each url or he can also delete all the urls from the database by pressing the clear-all button.when ever a delete command is envoked urls are deleted from the database. 
