# MANIPULATION USE CASES  

Reference: [RosToolingUserStoryImplementation](https://github.com/David-its-me/RosToolingUserStoryImplementation)

## MANI-01 - Sample movements

A company wants to demonstrate its expertise at its trade fair stand where a robotic arm should perform simple pick and place move- ment sequences in a repetitive cycle. There is not much time left for preparation, so they want to have the robot arm into operation as quickly as possible.

## MANI-02 - QR Detection and Decision Methodology of a Picking robot  

In the scenario a robotic arm is integrated into a production line, where smaller packets on a conveyor belt drive by. Currently, the robot is responsible to pick and sort out packets with a specific color from a conveyor belt. Now there is a need to have a more fine granular differentiation, which packets should be sorted out. Therefore the technical director decided to use labels with QR-Codes instead of the packet color. The currently deployed version of the software also contains a module, that is responsible to do the decision-making part, about packages which must be sorted out. This part of the software must be reimplemented. For that, there must be an algorithm which is able to detect and read a QR-Codes. Based on the information on the QR-Code there is another module needed, that decides if the packet must be picked.
  
## MANI-03 - Pick and place ball 

A toy manufacturer wants to have a packing robot that is able to pack objects in a cardboard box. In particular the manipulator should be able to pick a ball and place it in a carton box. The surrounding environment is very static. This means there are no people or moving objects around the robot. The ball and the box also always have the same size and position, the robot therefore needs little or no perception of its surroundings.
  
## MANI-04 Pick Box from shelf with GUI  

A pharmacy shop wants to build a system, that can automatically pick drug packings from a small warehouse within the shop. Until now the medicine boxes have been picked out manually by the working staff. An configurable robot shall be able to percept and pick and place small boxes. Also a simple GUI is installed at the counter to request medicine to be brought by the system.
