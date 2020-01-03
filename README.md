# Scopotic framework

Discover a multi-purpose framework for building automation system with mixed hardware and software interface.
Build your own solution for your need with the manager behavior you need.  
You just need to combine the manager type you need or make them.  
Interact with them via a simple extensible Api.
Find plugin or make one to interact with your hardware or software.
Build virtual object combining data and behavior from heterogene plugins for making a usefull virtual layer for making decision and automatisation rules.

##Targetes features :  
- Modular system,
- Extensible via plugin, 
- CQRS based system,
- lightweight
- Open source tests
- cross platform (dotnet core 3)
- simple query and command api
- optional builtin rest api


##System architecture :
###Internal Manager (can't be modified):  
- plugins manager
- reality layer manager
- virtual layer manager
- (event manager (event broker))

###External manager:
- data manager 
- (api manager)




##Other related project on github
###Full program project :
- console server (comming soon)
- windows services server (comming soon)
- windows services monitor
- windows configuration app
- 

###Availables external manager
- XmlFileDataManager

###Availables plugins
- (coming soon)


####Note: 
This project is still in development.
This free version of the framework will be limited to 100 nodes in the futur.

This project is managed by Scopollif.

#### version: 0.1
