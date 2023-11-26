1) Create a new ObjectARX project in Microsoft Visual Studio as an MFC Dynamic Link-Library (DLL).
2) Configured the project to build an ObjectARX application by making necessary changes in the C++ and Linker properties.
3) This involves setting the necessary compilation and linking options to enable ObjectARX development.
4) After that, add all required libraries in the project's properties settings.
5) It includes linking against the ObjectARX libraries and any other dependencies needed for developing AutoCAD applications.
6) Next step is to define the acrxEntryPoint function. This function serves as the entry point for the ObjectARX application.
7) It handles initialization and unloading messages, such as AcRx::kInitAppMsg and AcRx::kUnloadAppMsg.
8) TO implemente code to display the message "Hello in the world of AutoCAD" when the command "MYCOMMAND" is entered in AutoCAD. 
9) This involves defining a custom command function (e.g., MyCommand) and registering it using acedRegCmds->addCommand.
10) In summary, the described steps outline the process of creating an ObjectARX project, configuring it for AutoCAD development, adding necessary libraries, 
defining the entry point function, and implementing a custom command to display a specific message in the AutoCAD environment.
