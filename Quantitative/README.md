## QUANTITATIVE EVALUATION

RosTooling proposes a solution for developing robotic applications using model-driven development (MDD). The case of RosTooling is particularly interesting in the sense that it leverages the advantages of the ROS ecosystem, which has an extensive catalog of hand-crafted open-source components. 
In order to make use of this catalog, RosTooling offers static code analyzer solutions as well as introspection of running systems. In this way RosTooling positions itself as an optimal tool for system integration using as composition modules existing ROS packages that can be easily imported into the RosTooling user interface.

All the documentation about how to use the RosTooling is publicly available under [RosTooling documentation](https://ipa320.github.io/RosTooling.github.io/). Based on this set of instructions, we conducted real world experiments based on two applications areas manipulation and service robots. For each of the areas a set of use cases has been proposed, this repository holds the development of these cases using the RosTooling:
- [Manipulation](Manipulation/README.md)
- [Mobile Assistand Robot](Mobile_Assistant_robot/README.md)

Graphically the systems, thanks to the MDD proposed solution, are shows as:

<img src="Manipulation/MANI02_common/Ur5e_system.jpg" alt="Ur5e" width="600"/>

*Figure 1: Simplified view of a manipulation case using the RosTooling.*

<img src="Mobile_Assistant_robot/MOBI02/Cob_nav_sirius1.jpg" alt="cob_saturn" width="600"/>

*Figure 2: Simplified view of a mobile assistant robot case using the RosTooling.*

Technical related repositories:
- RosTooling source code: [RosTooling](https://github.com/ipa320/RosTooling)
- ROS2 embedded code generator: [rossdl](https://github.com/CoreSenseEU/rossdl)
- Python parsers (packed as a ROS package) for the ROS and ROSsystem models: [ros_model_parser](https://github.com/ipa320/ros_model_parser)
- Python implementation for the static code analyzers and docker containers setups for different ROS distros: [ros-model-extractors](https://github.com/ipa320/ros-model-extractors)
- Runtime monitoring pipelines:
  - ROS1: [rosgraph_monitor](https://github.com/ipa320/rosgraph_monitor)
  - ROS2: [ros2model](https://github.com/ipa-cmh/ros2model/)
- Eclipse update site: [RosTooling-update-site](https://github.com/ipa320/RosTooling-update-site)
