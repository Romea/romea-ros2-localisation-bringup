# 1 Overview #

This package provides tools to launch localization algorithms developed by ROMEA team. Three kind of localization are provided:  1)  **robot to human localization** able to estimate the position of a human leader in the reference frame of a follower robot based on a Kalman filter ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/romea_robot_to_human_localisation_core), [github](https://github.com/Romea/romea-ros2-robot-to-world-localisation-core)),  2) **robot to robot localization** able to estimate the pose of a leader robot in the reference frame of a follower robot based on a Kalman filter or a particle filter: ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/romea_robot_to_robot_localisation_core), [github](https://github.com/Romea/romea-ros2-robot-to-robot-localisation-core)) and 3) **robot to world localization** able to estimate the pose of a robot in map reference frame base on a Kalman filter or a particle filter ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/romea_robot_to_world_localisation_core), [github](https://github.com/Romea/romea-ros2-robot-to-world-localisation-core)). These algorithms can be run together or separately and use observations provided by common plugins such as **odo** ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/romea_localisation_odo_plugin), [github](https://github.com/Romea/romea-ros2-localisation-odo-plugin)) and **imu** ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/romea_localisation_imu_plugin), [github](https://github.com/Romea/romea-ros2-localisation-imu-plugin))  plugins and specific plugins  such as **gps** ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/localisation_gps_plugin), [github](https://github.com/Romea/romea-ros2-localisation-gps-plugin)) plugin or  **robot to human** ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/romea_robot_to_human_localisation_rtls_plugin),[github](https://github.com/Romea/romea-ros2-robot-to-human-localisation-rtls-plugin)), **robot to robot**  ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/romea_robot_to_robot_localisation_rtls_plugin),[github](https://github.com/Romea/romea-ros2-robot-to-robot-localisation-rtls-plugin))  and **robot to world** ([gitlab](https://gitlab.irstea.fr/romea_ros2/algorithms/localisation/romea_robot_to_world_localisation_rtls_plugin),[github](https://github.com/Romea/romea-ros2-robot-to-world-localisation-rtls-plugin)) rtls plugins. These plugins are used to converts data coming from embedded sensors to observations that can be used Kalman or particle. 

# 2 Node #

