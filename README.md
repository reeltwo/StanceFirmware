This firmware manages transition from two legs to three legs and back to two legs. It sets up a serial listern on hardware Serial1 (assuming a Mega, but could be changed to SoftwareSerial).

The serial commands to initiate the transtions are:

#TWOLEGS\r

and

#THREELEGS\r

The firmware also expects an analog value measuring the distance of the center leg as well as two IMUs. One attached to the yoke and the other level with the body. The two IMUs are used to calculate the yoke angle.

