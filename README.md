# mirte-ros-prebuilt-packages
Prebuilt packages for MIRTE robots

Commands on how to setup are in readme files for each branch:
- ARM64 main: [ros_mirte_humble_jammy_arm64](https://github.com/mirte-robot/mirte-ros-prebuilt-packages/tree/ros_mirte_humble_jammy_arm64/README.md)
- AMD64(x86) main: [ros_mirte_humble_jammy_amd64](https://github.com/mirte-robot/mirte-ros-prebuilt-packages/tree/ros_mirte_humble_jammy_amd64/README.md)
- ARM64 develop: [ros_mirte_humble_jammy_arm64_develop](https://github.com/mirte-robot/mirte-ros-prebuilt-packages/tree/ros_mirte_humble_jammy_arm64_develop/README.md)
- AMD64(x86) develop: [ros_mirte_humble_jammy_amd64_develop](https://github.com/mirte-robot/mirte-ros-prebuilt-packages/tree/ros_mirte_humble_jammy_amd64_develop/README.md)

Run setup commands, then:
```bash
sudo apt update
sudo apt install ros-humble-mirte-....
```

Prebuilt packages are generated in https://github.com/mirte-robot/mirte-ros-packages/blob/main/.github/workflows/ros-build.yml (main and develop branches)
