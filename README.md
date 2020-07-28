# Introduction
Arduino code(mpu6050_imu_driver/firmaware) employing rosserial to retrieve a quaternion from the mpu6050 DMP. Another ROS node(mpu6050_imu_converter) publishing IMU & Pose messages to ROS. 

Then, use the mpu6050_imu_converter package to publish IMU & Pose messages.

The package is tested on Arduino Uno compatible & Asus Tinker board(Raspiberry Pi or PC maybe OK).

# Demo
$catkin_make

$roslaunch mpu6050_imu_driver mpu6050_imu.launch

video on youtube -> https://youtu.be/ziUGnZDbtfc

# Explanation
<a href="https://memo.soarcloud.com/mpu6050%e3%82%92%e3%83%ad%e3%83%9c%e3%83%83%e3%83%88%e3%81%ab%e7%b5%84%e3%81%bf%e8%be%bc%e3%82%82%e3%81%86/">Explained in Japanese</a>
