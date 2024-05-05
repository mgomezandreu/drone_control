## Drone Control
This project is a simple drone control system to follow a simple trajectory. It is written in CPP with Mujuco.
Currently I'm experimenting with distance sensors and cameras to make the drone aware of its environment.

## Installation
Clone the repository and run the following commands:
```bash
git clone git@github.com:mgomezandreu/drone_control.git
cd drone_control
mkdir build
cmake -S src -B build
cd build
make
```
Run the program with:
```bash
./control
```
