# SafariApp
Safari app for public

Brief about project description:
===============================
This is  all about booking the safari ticket for public. 
There were different tariffs like adult, child, kids and student. And there are differant vehicles are available for safari like Jeep, Gypsy, Bus. ANd

Below are some use cases for the application :
user registration
user login
checking available vehicles
checking price list
booking

So, based on these criteria the safari ticketing system has been developed.

Below are the technologu/features implemented:
=============================================
	swagger configuration in order to make eassy fro api testing
	h2 in memory database to store the data.
	added log4j in order to trace the issues.
	actuators : to check appliction health status.		
	devtool : to do auto reload configuration in case of code change.	
	spring security	: added root api level basic authentication.	
	coding standard : followes below coding standards					
			proper package structure
			log implementation 
			defining util class and methods seperately
			dynamic file path configuration
			appropriate comments
			proper indentetions
			code alignments
			
Below are the Rest end points developed :
=======================================
	GET : http://localhost:8082/addSampleUserData
	GET :  http://localhost:8082/getAllUser
	POST : http://localhost:8082/getUserById?id=101
	POST: http://localhost:8082/register
	POST: http://localhost:8082/login?name=ram&password=123	
	GET : http://localhost:8082/getSampleVehicleData
	GET : http://localhost:8082/getAllVehicles
	POST : http://localhost:8082/addVehicle
	GET: http://localhost:8082/getPriceList
	POST : http://localhost:8082/booking
