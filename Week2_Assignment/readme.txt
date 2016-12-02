
Set up:
1.	Install Node and mongodb 
2.	download the code into your local machine to a folder AngularJS_Assignment
3.	open command prompt from the folder
4.	type "npm install", this will install all the node dependencies
5.	Go to MongoDB installed folder till bin,
		Run mongod.exe (make sure you have C:/data/db folder created)
6.	 
7.	Create a folder “views” in the AngularJS_Assignment folder to place your index.html (the main html page)
		(Use name "index.html" for the initial page in your angularjs application and place that in the "views" folder.)
8.	Create a folder “client”  in the AngularJS_Assignment and place ypur angular js code for the assignment in that folder
9.	Please follow the below instruction in your angular js code,

		While creating a router, mention template url as "client/<your path>" ("client/" should be appended with your template 				urls, since you are placing your code in the folder name "client")
		Use server calls as below:
			Creating an Student: /add   , Method: POST
			Viewing student details: /view   , Method: GET
			Updating student details: /update/:id  , Method: PUT
			Deleting student details: /delete/:id , Method: DELETE
11.	 run the app using "node app.js"
12.	Go to browser and hit url : http://localhost:8888/index	
