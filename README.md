# Cozy-Learning-Record-Store 

A project for third-year students of Telecom Bretagne. We are creating a Learning Record Store
for Tin Can (xAPI) as a cozy application in a special personal cloud called Cozy cloud.
This project will allow Tin can users to protect more their data and introduce the power of cozy cloud to eLearning world.

This application accomplishes three main tasks :

	1- The first and most important is its role as learning store record for applications 
	   using the standard Tin can (xAPI).
	   The Learning Record store uses Cozy cloud for the storage of Data (Statements,..).
 	   Applications implementing Tin can and willing to use this cozy app as an LRS can be
 	   "First-party client" or "Third-party client" towards Cozy cloud. In the second case 
 	   our cozy application will handle authentication and authorization processes (oauth2).

	2- Our application gives the opportunity to the owner of Cozy cloud to get a review on 
	   the Data stored in the cloud and execute some operations easily via our user interface. 
	   The range of these operations can be easily extended.

	3- Since authentication and authorization for "Third-party client" is not supported on 
	   Cozy cloud, we included an authentication and authorization server to our application 
	   to allow "Third-party client" applications (towards cozy) and implementing Tin can to 
	   use our cozy application as a Learning Record Store. 


Find more about:

Cozy cloud: [https://cozy.io/fr/](https://cozy.io/fr/)

Tin can: [http://tincanapi.com/](http://tincanapi.com/)

TinCan API Collecter: [https://github.com/ZelongChen/TinCan-API-Collector](https://github.com/ZelongChen/TinCan-API-Collector)
	
## License
	
See the [LICENSE](LICENSE.md) file for license rights and limitations (AGPL).
