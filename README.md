# PLC-based-Alarm-System
## Using Software "LOGO soft comfort v7"

*Analog input with resolution of 10 bits:*

**So,**

Input can be from [0 - 1024] units.

Now,

*If input below 200 and above 500, then system is in threat and threat alarm starts.

If input below 200 and above 900, then system is critical and shutdown alarm Starts.

If input is above 200 and below 500, then system is normal and every alarm is OFF.*

**To avoid the fluctuation at transition points i.e [200,500,900]. There is 50units windows between upper threshold and lower threshold.**

### Example:

#### System threat alarm starts when input crosses 500 but it will stops when input crosses 450.
