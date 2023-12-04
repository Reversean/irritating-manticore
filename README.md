# irritating-manticore

## Сборка проекта

```shell
rosdep install --from-paths src --ignore-src -r -y
```

```shell
catkin_make
```

```shell
source devel/setup.sh
```

## Запуск roscore

```shell
roscore
```

## Запуск rqt

```shell
rqt
```

## Запуск контроллера

```shell
roslaunch myrobot_control control.launch
```

## Запуск Gazebo

```shell
roslaunch myrobot_simulator gazebo_testwalls.launch
```

## Запуск rviz

```shell
roslaunch myrobot_description rviz.launch
```
