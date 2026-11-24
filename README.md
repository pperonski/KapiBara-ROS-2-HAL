# KapiBara ROS2 container

Container with ROS 2 and all required hardware drivers.

## Quickstart

To run container execute:

```bash
./run.sh start
```

Container should start then in seperate terminal you can execute any ros command using:

```bash
./run.sh cmd \<command\>
```

## Build container

In order to build container run:

``` bash
./run.sh build
```

In order to build container without cache run:

``` bash
./run.sh rebuild
```

## Other containers

- Container with main logic - <https://github.com/pperonski/KapiBara-ROS-2-General-Image>
- Container with Mojoco simulation - <https://github.com/pperonski/KapiBara-ROS-2-Mujoco>
