# Problem

  The idea of this assignment is that you produce a small ‘animation suite’ so that users
can run cartoons that I call footage (that is made up of frames). The frames are made
of little blocks – squares of colour. You will also allow editing of the footage in the
form of transformations (described below).
 
  The code in this will handle the underlying representation of the movie as a set of frames, and its storage in a file.
The code will also handle footage transformations. I have provided three Java
interface files that you must implement. YOU MUST NOT CHANGE THESE
INTERFACE FILES.

You must save the cartoon footage in the following format:
4

5

bbbbb

bbbbb

bddbb

bbllb

bbbbb

bbbbb

ddddd

lllll

ddddd

bbbbb…… lots deleted

The first number is the number of frames (4 in this case).
The second is the number of rows and columns of the picture (5).
Then come (in this case 20 (i.e. 4*5)) lines of characters. (I used b for background, l
for light and d for dark). You are provided with scotty.txt and spotty.txt example files
