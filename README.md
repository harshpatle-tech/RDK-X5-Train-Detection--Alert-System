# RDK-X5-Train-Detection--Alert-System
AI-based Train Detection and Communication System using RDK-X5

http://192.168.1.25:8000/TogetheROS/
ROS2 DNN Node + Relay (Terminal 1 aur 2)
#	Command	Note
T1	source /opt/tros/humble/setup.bash	ROS2 source karo
T1	ros2 launch dnn_node_example dnn_node_example.launch.py	Terminal 1 mein
T2	source /opt/tros/humble/setup.bash	Naye terminal mein
T2	python3 ~/train_relay_node.py	Terminal 2 mein
