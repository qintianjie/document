document
========

The sample include two part in web programe:  REST & WEB. Use the following skills:

Linux OS
MySQL
Maven   	-- Use parent-child to manage the project. 
		-- Configure jetty in the project to run and debut the project.
		-- Use Tag, Branch, Trunk to manage the version.

Git/GitHub  	-- Manage the project.
JUnit   	-- Write the test case to make the DB test automatically.
Log     	-- Log the information by the level.

MyBatis 	-- As a database framework to programe DAO project.
SpringIoC/Anno  -- As the component to manage the beans.
Jackson2        -- Let the REST api return json string.
RESTfur/Jersey  -- Offer the REST api for the user.

SpringMVC	-- For web project.
Tiles		-- For web project.
JSTL  		-- For web project.
	

Part 1: REST api.

	The sample was in user-rest project, that include user-rest-dao, user-rest-service, user-rest-api projects, also include the public projects: logger-slf4j-deps, mybatis-basemapper.
	
	Functions include CURD the user table. 

		 * GET : /user/{id}, get user by id.
		 * POST : /user, create a user.
		 * PUT : /user, modify a user.
		 * DELETE : /user/{id}, delete user by id.
		 * GET: /user?email=XXX, get user by email.


Part 2: Web project.

	The sample was in user-rest and user-register projects. That include user-rest-dao, user-rest-service, user-register-webcomponent, user-register-web, also include the public projects: logger-slf4j, mybatis-basemapper. 
	
	Functions include CURD the user table, verify the params to update the user.

		http://localhost:8083/users
