## APPLY: OCP to ADD to CANVAS of LINE, RECTANGLE, BUCKETFILL.

## CANVAS
- Should thinking about future commands.
- Must be draw FIRST.
- Contains another like LINE, RECTANGLE, BUCKET.

## LINE (NOTED) 
- Verify formula: |x1-x2| != |y1-y2| &&      { (x1 = x2) => VERTICAL, (y1 = y2) => HORIZONTAL }
- So should throws exception like "invalidCommand" -> message 'Currently only horizontal or vertical lines are supported.
- Diagonal line not supported

## RECTANGLE (NOTED)
- by draw 4 LINEs ?

## FillBucket (NOTED)
- Which Algorithm to fill like paint (Traversal ?)

## COMMAND <Line, Bucket, Rectangle> (HOW ABOUT SPIT DRAW COMMAND AND ANOTHER COMMAND ?)
- Need command parser to check invalid command.
  + Use Pattern Class to validate command by Regex.
- Need to create CANVAS first.

## ERROR HANDLING
- IllegalArgumentException (I/O)
- OUTSIDE

## What pattern should choose to "determine" and "operate" commands of whose (C, L, R, B, Q).
+ ????

## NOTE: the functionality of the program is quite limited but this might change in the future.