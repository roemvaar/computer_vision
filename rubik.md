# Rubik's Cube Solver using OpenCV on an Nvidia Jetson Nano

I've personally always found solving the Rubik cube as a though challenge, so I decided
to create an embedded system to help me solve this problem.

**Steps**:

1. Capture video
2. Convert image from BGR to HSV
3. Separate 6 color images using InRange
4. Find area using FindContours
5. Use Kociemba's two-phase algorithm for solving Rubik's Cube

Work inspired by Yassine Hamdaoui linkedin's publication:
https://www.linkedin.com/posts/yassine-hamdaoui_rubiks-cube-solution-using-opencv-by-daizyu-activity-6750823443706466304-4gJy

