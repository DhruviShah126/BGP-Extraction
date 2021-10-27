# BGP-Extraction

This program parses through a given BGP routing information file. It will find and extract the 7th field of each line of the file. It will clean up that filed making sure there are no duplicate numbers and any number in the bracket is ignored. Once that is done, it will keep track of the number of neighbors each AS has and display the top 10 with the highest number of neighbors.
