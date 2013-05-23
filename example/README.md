
To run this basic example, first compile the code to a jar file. That jar file is refered to as treemappa.jar in the remainder of the file.

Create a CSV file of the data. 

Create a settings.cfg file that specifies fonts, colors, options, etc. These can be placed in the command below but are easier to see and manipulate in a separate file

Modify colors.ctb if changes to the colors are desired.

Run the following command (assuming the compiled library is called treemappa.jar and in the same location)
    java -jar treemappa.jar loadConfig settings.cfg

This will produce a file wikipedia.svg identical to the example output included (wikipedia-example.svg)
