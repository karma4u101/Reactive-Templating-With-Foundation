Reactive Templating With Foundation 
===================================

**This is work in progress!** You can take a peek at it right now but i suggest you also check back later for a better experience. 

The intention of this example is to show some of Lifts templating features in conjunction with the front-end toolkit 
[ZURB/Foundation](http://foundation.zurb.com/) and in particular fondations reactive semi-liquid, mobile-scaling grid.  

One of Lift's many great features is its clean and flexible templating system. For convenience and to give some styling 
to Lift and it's templates Lift comes by default, at this writing, bundled with [blueprint](http://blueprintcss.org/) as hooked 
up CSS framework here you will see blueprint replaced by foundation which lets you utilize a very powerful [reactive web design](http://www.google.com/search?client=ubuntu&channel=fs&q=scalability&ie=utf-8&oe=utf-8#sclient=psy-ab&hl=sv&client=ubuntu&hs=7bM&channel=fs&source=hp&q=reactive%20web%20design&pbx=1&oq=&aq=&aqi=&aql=&gs_sm=&gs_upl=&bav=on.2,or.r_gc.r_pw.,cf.osb&fp=1d39e901c42700bd&biw=1334&bih=833&pf=p&pdl=500) 
with mobile scalability. 
  
  
This _unofficial*_ example is intended for those of you who need some compact and concise running and mostly ;) simple to follow example of a particular 
feature or concept in Lift.

After many years of Java EE development I started look at Scala/Lift in May 2011 so there may be some none "best practice" stuff in there 
and if you find something you think could be done in a more Scala/Lift fashion please let me know.

Improvements, contributions and suggestions are welcome!

best regards Peter Petersson 

Quick Start
-----------
The only prerequisites for running this Lift example is that you have Git and Java installed and configured on the target computer.
You don't need to use it but the project also includes a Eclipse plug-in for browsing and following/working with the code, see the Scala IDE section.   

1) Get the examples

	git clone git@github.com:karma4u101/Reactive-Templating-With-Foundation.git
	cd Reactive-Templating-With-Foundation

2) Update & Run Jetty

There is also a sbt.bat for windows users.

	./sbt update ~container:start

3) Launch Your Browser
	
	http://localhost:8080/

###Database backend

For demonstration purpose and easy setup this example uses a in memory database. 

Scala IDE for Eclipse
---------------------
Sbteclipse provides SBT command to create Eclipse project files

1) Usage

	project$ ./sbt
	> eclipse 

2) In eclipse do: 

	File ==> Import...
	Select General ==> Existing Project into Workspace 
	Use "Brows" to look up the project root ....

User powered basic example 
==========================
**(*)** This is a _unofficial_ Lift user powered basic assembly example which means it is a work based on the 
sound foundation of Lift and done by a developer who uses Lift for development ;), sharing it with others.