# MyHouse-Mathematica
Drawing houses with Mathematica.

ClearAll[House];
Graphics[{Gray, Rectangle[{3.5, 6.5}, {4, 7.75}], Yellow, 
  Rectangle[{0, 0}, {5, 6}], Red, 
  Triangle[{{0, 6}, {5, 6}, {2.5, 8}}], Brown, 
  Rectangle[{2, 0}, {3, 2}], Lighter[Blue], 
  Rectangle[{0.5, 4}, {1.5, 5}], Lighter[Blue], 
  Rectangle[{3.5, 4}, {4.5, 5}]}]
