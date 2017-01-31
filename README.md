# Fr02

## How to use

## Installation
### From install script
##### 1. Create **catkinized**  workspace.
##### 2. Clone **forest_robot_project** and this repository.
```bash
$ cd <catkin_ws>/src
$ git clone git@github.com:Nishida-Lab/forest_robot_project.git
$ git clone git@github.com:Nishida-Lab/fr02.git
$ cd ..
$ rosdep init -i -y -r --from-paths src --ignore-src
$ catkin_make
```

### Run
```bash
$ source devel/setup.bash
$ roslaunch fr02_gazebo fr02.launch
```

Play!!! Do it !!!


