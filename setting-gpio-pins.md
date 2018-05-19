GPIO information is stored in 
/sys/class/gpio
echo "4" > export
echo "out" > gpio4/direction : Gpio pin 4 is output pin
echo "1" > gpio4/value
echo "4" > unexport
Chip: MCP3008 : Analog to digital converted .. reading Serial Peripheral Interface.
motor_driver_ L293D.py can drive two motors and allow 1 amp of current

