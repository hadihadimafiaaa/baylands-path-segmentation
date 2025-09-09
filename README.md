# baylands-path-segmentation
Trained a U-Net (MobileNetV2 encoder, pretrained on ImageNet) for multi-class segmentation. Semantic segmentation of drone camera frames in the Baylands Gazebo world. Dataset collected using PX4-Autopilot x500_mono_cam_down camera, published via ROS 2 Humble with rosgzbridge. Classes: background, path, road.
