# rosbag_plotter_matlab

A MATLAB script to easily plot graph from ROS bag 

## Download 

From a command line:
```
git clone https://github.com/MukilSaravanan/rosbag_plotter_matlab.git
```

## Installation

1) Go the specified directory where you have cloned the repository 
![go_to_the_directory](https://user-images.githubusercontent.com/47444101/189541384-0e05b458-baa3-4205-8b0f-04d54872b982.png)

2) To open the Set Path dialog box, on the Home tab, in the Environment section, click Set Path
![set_path](https://user-images.githubusercontent.com/47444101/189541464-d35515b9-66fc-4b42-8512-222ac8ed56d6.png)

3) Click on Add Folder and select the directory you have cloned the repository 
![add_folder_to_path](https://user-images.githubusercontent.com/47444101/189541473-97e04090-cfe6-4454-85b1-1fc2c7980553.png)

If the above are performed correctly, you see the path as shown the below image. Click on Save
![set_path_save](https://user-images.githubusercontent.com/47444101/189541573-5a6f6b0d-79d7-4332-9a1b-add602a3d350.png)

## Usage

1) Run the command in the command window
```
plot_rosbag()
```
![run_code](https://user-images.githubusercontent.com/47444101/189541658-e9d40958-86aa-4b4c-a34d-3d54d95446eb.png)

2) In the pop-up window, select the ROS bag that you want to visualize
![select_rosbag](https://user-images.githubusercontent.com/47444101/189541758-f914fe2f-3887-471f-aeb1-b1eff47b8739.png)

3) From the rostopics displayed in the command window, select a rostopic that you want to visualize. For eg., For `/odom`, enter 2 in the command window.
![select_rostopic](https://user-images.githubusercontent.com/47444101/189541852-86710b9f-75ce-4e78-ba62-f157c882e34e.png)

4) Now, you will see all the variables in the selected rostopic. For eg., to plot `twist/twist/linear/x` in `/odom` rostopic, enter `Twist.Twist.Linear.X` in the command window
![select_ros_variable](https://user-images.githubusercontent.com/47444101/189542014-f7323a1e-bd36-4977-ba08-189ee2fa100d.png)

5) Enter the name of the quantity and its unit, enclosed with quotes. For eg., `'velocity,m/s'`; This will appear as `velocity (in m/s)` in the graph
![enter_ylabel](https://user-images.githubusercontent.com/47444101/189542241-1ff63489-43a8-43d4-8a83-71f03e4083ca.png)

The graph will be displayed as show in the below image.
![displaying_graph](https://user-images.githubusercontent.com/47444101/189542304-86fceeda-725a-46b0-9c47-ef241610bcdb.png)

## Graph
![graph](https://user-images.githubusercontent.com/47444101/189542325-a3698394-7328-4980-94f9-4e7c4ba49a5a.png)


