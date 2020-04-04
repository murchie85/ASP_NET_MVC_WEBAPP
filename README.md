# WEB APP ASP.NET MVC 


![image](https://miro.medium.com/max/638/1*fdmEnFOCH8oDVo8mlQG2jg.jpeg)

## ASP & MVC

  
- **ASP** is the umbrella in which microsoft puts in all of their web focused tools and applications. Used to stand for `active server pages` which was web forms (the old microsoft forms). 
- **MVC** is one of the things under the umbrella, it stands for `model view controller`. 
- MVC is a UI user centric patter, it doesn't cover business logic or data access or anything behind the scenes. 
- The MVC can easily plumb in existing backend logic from other console/dekstop applications. 
- So in many cases we can just change the user interface rather than the application. 

C# sharp is the code that sits in the backend, the user only sees HTML, CSS and javascript as usual.   

### CONTROLLER 

This is the core MVC is the controllers, this is the backbone of MVC.  
The controllers `like the views with the data`, it is controlling the application. 



## STARTING UP   

Create a new application, make sure you select the one that says `web application`.  
  
![webapp](image/webapp.png)
  
   
Chose template as MVC, Web API is super awesome to look into and decouples from front end (focuses on just back end stuff. ).  
Now select no authentication, there is code for auth methods.   
When you select OK, the bottom left will import a bunch of components and download nugget packages.

## Nugget 
  
Microsoft package manager like brew or yum etc. So we can pull in jquery, bootstrap etc.  
Be careful, you may not be able to just install all the latest ones: You will need to look for stable versions and compatability etc. 
**NOTE** best to uncheck 'include prerelease'. 

