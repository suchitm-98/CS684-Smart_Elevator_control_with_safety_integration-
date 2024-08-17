
Strategy - First thought how the lift will work on paper. Functionality for going up and down is added at first floor. Go UP at ground floor and go down at 2nd floor. I took different states for moving up and down when user is inside ( User Destination) the or when the lift is empty (when user is empty).

Assumptions -   1) The user has to press the buttons provided at outside lift interface to go inside the lift.
		2) The user has to press for a desination after going inside other wise the lift will go idle.
		3) Any one of the lift can be assigned to a request.
		4) Once both the lift are busy the other requests go in a queue.
 (L1/L2userDestination/
  floor1UP, floor1Down				Output (Changes)
 ,floor0UP, floor2Down)		

	floor1UP				allocation of Lift1 (may be lift 2 can also 							be assigned as bith were idle)
						allocated lift moves to floor 1 to the user
						Door opens
	L1userDestination=2			Lift moves upwards to serve user request
	floor0UP 				allocation of Lift2
						Now Lift 2 also moves and both the lift 						works parallely.


YT URL : https://youtu.be/fvUGZFAO3rk
