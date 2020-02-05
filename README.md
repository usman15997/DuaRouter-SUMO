# DuaRouter-SUMO
This is an example of how to use DuaRouter in Simulation of Urban Mobility (SUMO) 
This repository contains simple example of how to use Dynamic User Assignment (DUA) router in Sumo. I made a simple road network and tested it with Duarouter.
When you install SUMO with all packages, you will find these two (duaIterate.py and Costmemory.py) in SUMO's tools folder.
Copy those files in your folder and make a network file with NetEdit or make it manualy with simple text editor.
Make a route file or trip file or flow file 
Place both all 4 files (duaIterate.py , Costmemory.py , .Net file and .trips.xml) in one directory and open cmd and change the location to that folder containing these file.
Type this command python duaIterate.py -n <name of your network file> -t <name of your trip or route file> -l <any integer value to specify no. of iterations>
for more details visit https://sumo.dlr.de/docs/DUAROUTER.html 
