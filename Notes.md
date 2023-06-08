# Notes

## Outline:
Create working concept of a Traffic Management Center (TMC) sending traffic control messages to Road-side Units (RSU's) which relay the messages to vehicle On-board Units (OBU's).

Control (TMC) -> Road Infrastructure (RSU) -> Cars (OBU)

## Overall To Do:
- Figure out hardware
    - TMC := NVIDIA Jetson Nano
    - RSU := Rasberry Pi
    - OBU := Rasberry Pi
- Figure out communication
    - (TMC -> RSU) := ethernet
    - (RSU -> OBU) := internet
        - Must emulate DSRC communication
        - Need to follow DSRC standards
- Messages should result in control limits for the cars 
    - ie. capping speed in simulated construction zone

## Next To Do:
- Get Jetson up and running