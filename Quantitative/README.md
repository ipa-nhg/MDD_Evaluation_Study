## QUANTITATIVE EVALUATION

RosTooling proposes a solution for developing robotic applications using model-driven development (MDD). The case of RosTooling is particularly interesting in the sense that it leverages the advantages of the ROS ecosystem, which has an extensive catalog of hand-crafted open-source components. 
In order to make use of this catalog, RosTooling offers static code analyzer solutions as well as introspection of running systems. In this way RosTooling positions itself as an optimal tool for system integration using as composition modules existing ROS packages that can be easily imported into the RosTooling user interface.

All the documentation about how to use the RosTooling is publicly available under [RosTooling documentation](https://ipa320.github.io/RosTooling.github.io/). Based on this set of instructions, we conducted real world experiments based on two applications areas manipulation and service robots. For each of the areas a set of use cases has been proposed, this repository holds the development of these cases using the RosTooling:
- [Manipulation](Manipulation/README.md)
- [Mobile Assistand Robot](Mobile_Assistant_robot/README.md)

Technical related repositories:
- RosTooling source code: [RosTooling](https://github.com/ipa320/RosTooling)
- ROS2 embedded code generator: [rossdl](https://github.com/CoreSenseEU/rossdl)
- Python parsers (packed as a ROS package) for the ROS and ROSsystem models: [ros_model_parser](https://github.com/ipa320/ros_model_parser)
- Python implementation for the static code analyzers and docker containers setups for different ROS distros: [ros-model-extractors](https://github.com/ipa320/ros-model-extractors)
- Runtime monitoring pipelines:
  - ROS1: [rosgraph_monitor](https://github.com/ipa320/rosgraph_monitor)
  - ROS2: [ros2model](https://github.com/ipa-cmh/ros2model/)
- Eclipse update site: [RosTooling-update-site](https://github.com/ipa320/RosTooling-update-site)