GPIO information is stored in 
/sys/class/gpio
echo "4" > export
echo "out" > gpio4/direction : Gpio pin 4 is output pin
echo "1" > gpio4/value
echo "4" > unexport
