# Ex.No.-1.1-Design and Draft the given 2D Sketches in modelling software.

## AIM

To sketch the given drawing with dimensions using fusion 360 tool.

## REQUIREMENTS

  1. Autodesk fusion 360
  2. Windows 10
  3. 16 GB of RAM (integrated graphics recommend 2 GB or more)
  4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
  
## PROCEDURE

1.	Open new file and then select sketch icon.

<img width="583" height="561" alt="Screenshot 2026-10-05 101307" src="https://github.com/user-attachments/assets/71a10641-df97-462a-995a-f36c1e37e56f" />

2.	Select the XY plane and it you will see the horizontal and vertical axes.
Use the vertical axis as the centreline.
Use the horizontal axis through the centre of the central Ø40 feature as your main horizontal reference
<img width="461" height="521" alt="Screenshot 2026-10-11 174747" src="https://github.com/user-attachments/assets/a42ced7c-746f-4953-94f4-45c75b1433ab" />

3.Select Line.
Draw a vertical line through the origin.
Make it a Construction line.
This is extremely important because the entire part is symmetrical.
You can also draw horizontal construction lines for the different centres.

4.On the vertical centreline, create a point 65 mm above the origin.
This is the centre of the top circles.
Now draw:
Inner top hole
Circle
Diameter = 20 mm
Outer top 
Circle
Diameter = 32 mm
So:
Outer = Ø32
Inner = Ø20
The difference gives a 6 mm wall around the top hole


5.The side holes are located 26 mm below the main horizontal centreline.
Since the drawing is symmetrical:
Left hole centre = 26 mm below horizontal centreline
Right hole centre = 26 mm below horizontal centreline
Draw a horizontal construction line 26 mm below the origin.
Now place two points on this line, one on each side of the vertical centreline.
The drawing gives R7.


6.The outer lug dimension is R10.
At each side-hole centre:
Draw a circle.
Set radius to 10 mm.
So:
Left outer lug = R10
Right outer lug = R10
The hole is R7 inside an R10 outer radius.
Therefore the lug has:
10 − 7 = 3 mm wall thickness


7. Select Center Diameter Circle.
Put its centre at the main horizontal/vertical intersection.
Enter Ø66.


8.Now look at the two long curves running from near the top Ø32 circle down toward the Ø66 region.
Both are labelled:  R64
These are two R64 arcs, one on each side.
You can construct the left one first.
Select Arc → Tangent Arc.
Select the left side of the Ø32 outer circle.
Create the arc downward.
Make the arc tangent to the relevant body curve.
Apply the radius constraint:R64
Then repeat on the right side:R64
Because the part is symmetrical, you can also make one side and Mirror it.

9.Look at the curves approaching the side lugs.
The drawing shows:R20 These are the large curved transitions between the main body and the side-lug region.
Again, make the left side first.
Use:Arc → Tangent Arc and apply:R20
Make sure the arc is tangent to:
the main Ø66 body curve
the region leading toward the R10 lug
Then mirror it to the right.

10.ear the bottom of each side, between the side lug and the bottom portion, there are smaller curved transitions. The drawing gives:R10
So create the left transition arc and set:R10
Then create/mirror the right:R10
These should smoothly connect the side-lug region to the lower central region.

11.The bottom hole is on the vertical centreline.
Its centre is: 24 mm below the side-hole centreline.
Since the side holes are 26 mm below the main horizontal centreline: 26+24=50
Therefore the bottom-hole centre is:50 mm below the main horizontal centreline
So: Draw a vertical construction line,
      Locate a point 50 mm below the origin.,
      Draw the bottom hole at that point.
      
12.Now we come to the unusual-looking opening in the centre.
The drawing gives:Ø40
So first:  Draw a circle centred at the origin.
               Set its diameter to: Ø40
This is your base/reference for the central opening.

13.The central shape has four similar curved portions.
The dimension given is:
R6
You need four R6 arcs:
one at the top
one at the right
one at the bottom
one at the left
The easiest way:
Make the top R6 first
Create a small circle/arc.
Set its radius to 6 mm.
Position it on the vertical centreline.
Trim it so that only the required semicircular portion remains.
Then:
Pattern it
Use Sketch → Circular Pattern.
Select the R6 geometry.
Centre of pattern = origin.
Quantity = 4.
Angle = 360°.
That gives four identical R6 features at 90° intervals.

14.Once the R6 features are created:
Use Trim.
Remove the unwanted portions of the Ø40 circle.
Keep the alternating straight/curved shape shown in your drawing.
The result should look approximately like the white central opening in your image. 
<img width="407" height="470" alt="Screenshot 2026-10-05 101335" src="https://github.com/user-attachments/assets/dbf3388f-6bf7-4227-9c94-548fd8cea06d" />


15. Use symmetry instead of drawing everything twice Draw only the LEFT side
Construct:
left half of Ø66
left R64
left R20
left R10
left R10 lug
left R7 hole

16.Give Finish Sketch and Switch to Drawing mode and plot the sketch.  
<img width="629" height="296" alt="Screenshot 2026-10-05 101402" src="https://github.com/user-attachments/assets/8f789734-8953-49f6-92d2-7059e6650c5c" />

<img width="492" height="561" alt="Screenshot 2026-10-05 101420" src="https://github.com/user-attachments/assets/7812b2ca-9004-4e6f-b1ac-9a010fcca84b" />

<img width="471" height="529" alt="Screenshot 2026-10-05 101440" src="https://github.com/user-attachments/assets/f679160f-b70a-4bbe-8b76-b002455c4a6d" />




## SKETCHS
<img width="1080" height="795" alt="WhatsApp Image 2026-10-08 at 9 47 00 AM" src="https://github.com/user-attachments/assets/c3b6b969-43f1-459e-a571-c87dbb5fe14d" />

## OUTPUT

<img width="864" height="610" alt="Screenshot 2026-10-05 124309" src="https://github.com/user-attachments/assets/4b70409a-6ed0-47ff-8c7a-160d4daa9364" />


## RESULT
Thus the given sketch is drawn and drafted using fusion 360 tool.
