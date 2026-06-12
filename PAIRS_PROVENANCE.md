# PAIRS provenance

This package is a third-party external vendored into the PAIRS UAV system under
its **upstream name** (not renamed to `pairs_*`).

**Fork chain:** [christianrauch/camera_ros](https://github.com/christianrauch/camera_ros) → [ctu-mrs/libcamera_ros](https://github.com/ctu-mrs/libcamera_ros) → pairs-lab/libcamera_ros

PAIRS tracks the CTU-MRS fork; the only PAIRS-side edits are dependency rewiring
(`mrs_* → pairs_*`) and minimal build fixes for ROS 1 Noetic / Ubuntu 20.04.
Original copyright and licenses are retained from the upstream project.
