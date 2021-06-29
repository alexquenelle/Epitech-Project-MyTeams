# Epitech-Project-MyTeams

The Goal of this project is to create a Microsoft Teams like in C, project done in a group of 3 students in 1 month.

How to build ? $ make

How to launch the program ? You first needs to export the library used by the server and the client like that : $ export LD_LIBRARY_PATH=libs/myteams/.

Then, you have to launch the server : $ ./myteams_server [the port you want]

And, on an other terminal execute the client binary : $ ./myteams_client 127.0.0.1 [the port you just gave to the server]

You can find all of the recognazied commands by the client in the rfc1550.txt file a the route of the project.
