# reprapaluextrusionreplacement
Designs for a 3D printed replacement of Aluminium extrusion frames on Reprap 3d printers. 

Here are the main advantages and disadvantages that I can see of having a 3d printed frame:

Advantages:

    Make the printer more self replicating (I think if it was possible it would be one of the highest percentage self replicating printers)
    Reduce the number materials needed to create a kit for people having trouble sourcing the parts like me
    Potentially reduce cost (although maybe not by a lot)
    Make it easier for people to experiment with different designs for the frame
    You can have it in what ever colour you want


Disadvantages:

    Much longer print time
    Potentially weaker frame


What I'm showing is where I have got to when I ran out of time, I would really love it if others could pick up where I've left off. I wont have access to my printer for the next few months but very happy to help in other ways.

The current design was done in Tinkercad and is quite simple, there are three different parts:

    Internal rods of 100mm in length

external sheathes (100m length) which come in two versions which can be shortened to create different length frame sides.

    end pieces which will screw into the existing corner pieces
    middle sheathes which are just a long tube. 


There were several previous iterations that were simply too complicated, I think my current approach has a few strengths:

    The end results seem very straight
    Uses PLA which means you don't need a heated bed
    The parts are easy to print and can be printed at a higher temperature to ensure good layer bonding
    The parts are printed with the rods lying down and the sheathes on their ends so printed layers run in different directions meaning the parts are strong in all directions.
    Simple construction, you only need a wooden mallet or some other tool to encourage the parts together
    Strong joins between parts, the inner rods join in the middle of the outer sheathes
    The longest dimension of parts is 100mm meaning it can be printed on a small print volume printer.


Printing notes:
I printed everything seen with Hatchbox PLA using a Printrbot Simple Metal with a E3D V6 head with 0.3mm nozzle. I used a 0.6 outer shell, 35% infill, 2mm layer heights and printed at 217 degrees C with a cooling fan.

The internal rods are printed at around 95% size so they fit snuggly inside the outer sheathes. I printed shorter test pieces to find the right scale however shorter pieces have slightly less friction when pushing them together, I found 96% worked fine with the test pieces but 95% worked much better with the full size pieces. It also helps a lot in getting the parts to fit well to scrape the corners of the internal rods a bit with a sharp knife.

Issues

    The time it takes to print the pieces is quite long
    Tolerance for print size of internal rods is very small, however its easy to make shorter lengths to check tolerances
    The direction for the join for the internal rods is the sample as the direction for the direction of the print layers in the outer sheath meaning this could be a weak point but I think this could be fixed with glue.
    You have to scrape the edges off the internal rods so that the size is correct for the sides of it to grip the sides of the outer sheath.
    Once the parts are put together its not possible to take them apart again
    Whilst this maintains the width of the Aluminum you're not able to screw the other printed parts into the rods so would have to adapt the or make much wider rods to accommodate screw holes, here is a test piece.
    Image error
    Running getimagesize() on the image data failed
    open image URL


Ideas for future versions

    use a glue to join parts together, perhaps using a very rigid glue e.g superglue or araldite to increase rigidity of the frame. This could help with both the potential weak point in the middle of each section and make it easier to push the parts together because it would reduce friction when inserting the rods
    Round the edges of the internal rods
    Create some sort of mark on the internal rods so it is clear where the middle of the internal rods are
    Use transparent material to see when the parts are fitting together correctly


