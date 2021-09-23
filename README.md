# SafariApp
Safari app for public

Brief about project description:
==========================
This is  all about booking the safari ticket for public. 
There is different tariffs like adult, child, kids and student. And there are different vehicles are available for safari like Jeep, Gypsy, Bus. 

In the generated ticket customer can see there name, age, At what date/time ticket is issued , vehicle type and its vehicle number to identify, seat number etc. 
In the other hand Safari Management can monitor the dashboard with all booked ticket details day to day. Also they can store all old records in the database. 

Below are some use cases for the application :
   1. user registration
   2. user login
   3. checking available vehicles
   4. checking price list
   5. booking
   6. writing json response into file (for getAllUsers and getAllVehicles API)

So, based on these criteria the safari ticketing system has been developed.


Below are the features implemented:
================================
1.	swagger configuration in order to make easy for API testing
2.	covered unit test cases
3.	h2 in memory database to store the data.
4.	added log4j in order to trace the issues.
5.	actuators : to check application health status.                     
6.	devTool : to do auto reload configuration in case of code change.               
7.	spring security   : added root api level basic authentication.           
8.	coding standard : followed below coding standards                                                                          
•	proper package structure
•	log implementation 
•	defining util class and methods seperately
•	dynamic file path configuration
•	appropriate comments
•	proper indentetions
•	code alignments
                                                
Below are the Rest end points developed :
==================================
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
                
