print ("This program calculates the distance a suspended object falls, given a gravity and time")
# Get gravity from user
gravity = input ("Enter gravity number:")
# Convert string to int
gravity=int (gravity)
# Get fps from user
fps= input ("game fps:")
# Convert string to int
fps=int(fps)
# Get number of frames from user
frames=input ("Number of frames")
# Convert string to int
frames=int (frames)
# Calculate time object is falling
time= frames/fps
# Calculate distance in pixels objecthas fallen
distance= 1/2 * gravity *time
print("It will drop, distance, pixels in, time, seconds")
# Output time to user
