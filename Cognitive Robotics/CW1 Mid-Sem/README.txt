Project made by Gargeya Sharma, QMUL
220278025

To run this project perform these commands first:
-> Either run ros (version:"noetic") shell OR execute command: 'source ~/.bashrc'
-> Then we need to setup the catkin workspace with the command: 'source ~/catkin_ws/devel/setup.bash'
-> Unzip the cr_week6_test.zip file inside '~/catkin_ws/src/' directory
-> More to catkin workspace with command: 'cd ~/catkin_ws'
-> Install additional python dependencies used in this project:
        To implement Bayesian Network we are using: pomegranate,
        So, run 'pip install pomegranate' to install this package
-> Open the /cr_week6_test/package.xml file with your preferable editor and add this line to allow 
        executing pomegranate to run at execution time: '<exec_depend>pomegranate</exec_depend>'
-> Build the catkin workspace with: 'catkin_make'
-> Move to our package: cr_week6_test with command: 'roscd cr_week6_test'
-> Execute the launch file with: 'roslaunch cr_week6_test human_robot_interaction.launch'

The last step will start all the nodes, topics and service to complete the given task