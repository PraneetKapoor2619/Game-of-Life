# Game_of_life  
  
Here is a simple project I did using Python in which I implement Conway's "Game of Life". Users can select the dimensions of the world, cells which are supposed to be alive during the first generation, and can also save a generation.  
Just run golv0_2.py and you will get an idea on what is going on. The status of the grid at each iteration is stored into a file, which slows down the speed of program. Also sometimes more data is to be written onto the file and sometimes less, so that gives the simulation a weird laggy affect. To minimise it, I have used an explicit sleep statement which somewhat uniformatize the lagginess. If I had an SSD, this speed would be much higher.
