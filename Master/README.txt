Author: Henry Van Horik
Student Number: 0966956
Course: INFO6025 - Configuration and Build
Project: Project3
Git: https://github.com/hvanhorik-GDP/INFO6025---Project3.git

Soure directory : ./Master/Master/
Source File: Master.vcxproj
Build Command: 
"C:\..../msbuild.exe" Master.vcxproj /p:Configuration=Release /p:Platform=x64 /t:project_03
Output Directory: project_03

To run the program:

Master.exe								- Defaults to PhysicsLibrary
Master.exe GraphicsLibrary.xml			- Selects the library
Master.exe PhysicsLibrary.xml


******Old readme from original projects for Michael


This is a readme for all three projects 

INFO6044 - Engine frameworks & patterns
INFO6028 - Graphics
INFO6019 - Physics and simulation

To build:
	Select Release/x64 target
	right click on project "Master" and hit build

 I have placed searches in the code so you can track down examples for what I am discussing

 Select Search: 
	 Enter the project code. "INFO6044"
	 Pulldown "Entire Solution"
	 Pulldown "Find All"
		- This will find all references to the code that is implmenting specific stuff

You should start with "INFO6044 Engine frameworks & patterns" as it will give a good overview of the code
Then "INFO6028 - Graphics" 
Last "INFO6019 - Physics and simulation"

The same code will run all projects. They just need a different external script/xml file.
To change enter the following:
   Select "Master"
   Right-click/Properties
   Debugging
   Command Arguments
   Enter either "GraphicsLibrary.xml" 
   or "PhysicsLibrary.xml"

 This switches back and forth between the two projects.

