# Arduino-nano33ble-profiling

In windows powershell  
usbipd list  
usbipd attach --wsl --busid 2-8  
usbipd bind --busid 2-8  

compile  
arduino-cli compile --fqbn arduino:mbed_nano:nano33ble /home/woong/mnist/mnist.ino  

upload  
arduino-cli upload -p /dev/ttyACM1 --fqbn arduino:mbed_nano:nano33ble /home/woong/mnist/mnist.ino
