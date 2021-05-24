# remote_rviz


If you want to remotely see the rviz in the raspberrypi, follow the steps below

#Set the master IP and ROS IP on the slave PC(raspbeerypi)

$export ROS_MASTER_URI=http://{raspberryPi's Ip address}:11311/

$export ROS_IP={slave's IP address}

#Modify "/etc/hosts" file in order to resolve master's name to IP

$sudo gedit /etc/hosts

#add the following line to "hosts" in the format of

{raspberryPi's Ip address}   raspberrypi

#Save and close


The detailed steps are here 
https://github.com/ut-ims-robotics/tutorials/wiki/Running-ROS-over-multiple-computers#Example_case


