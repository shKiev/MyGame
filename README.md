                This is a python3 game with pygame and random libs.
                take a test

                #look at pygame lib and part of it.

                #notes : 
                        Note that player_speed is a list of two elements: horizontal (x-axis) and vertical (y-axis) velocities. Therefore, the horizontal speed is player_speed [0] , the vertical speed is player_speed [1] . When hitting the lower bound, we only need to change the vertical velocity, so the full test would look like this:

if player_rect.bottom >= HEIGHT:

    player_speed[1] = -1

Similarly for the right side:

if player_rect.right >= WIDTH:

    player_speed[0] = -1
