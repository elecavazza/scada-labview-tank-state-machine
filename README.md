![labview tank logo](./pictures/labview-tank-logo.png)

# scada-labview-tank-state-machine

SCADA Tank State Machine using LabVIEW Datalogging and Supervisory Control Module

## State Transition Table

| STATES               | Filling Button | Emptying Button |
|----------------------|----------------|------------------|
| State 1 - Idle       | 0              | 0                |
| State 2 - Filling    | 1              | 0                |
| State 3 - Emptying   | 0              | 1                |


## Block Diagram

### Idle State:  

![](./pictures/block-diagram-idle-case.png)

### Filling State:  

![](./pictures/block-diagram-filling-case.png)

### Emptying State:  

![](./pictures/block-diagram-emptying-case.png)

## Front Panel

### Controls and indicators:  

![](./pictures/front-panel.png)