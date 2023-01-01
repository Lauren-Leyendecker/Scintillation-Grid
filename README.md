# Scintillation-Grid-NEW
This program displays four versions of a Scintillation Grid on a 950 x 650 cyan background. Each grid consists of a black square, a grid of gray lines (both vertical and horizontal), and a white circle drawn at the intersections of the lines. The diameter of the circles are larger than the width of the lines, but the circles never cross outside of the lines, since, at the point in which lines intersect, there is a bit more room for the circle.

Formulas used to create the circles: (1) diameter of the circle = width of the line + extra bit; (2) Extra bit = 40% of the width of the line (truncated); (3) the extra bit must be at least 4 pixels, or it won’t be visible and the illusion won’t work.
