# Humanoid Black Knight
Exoskeleton-style Teleoperation and Imitation Learning.


## Testing teleoperation
To start testing teleoperation.

    ssh jetson@192.168.3.92
    roslaunch mobile.launch
    roslaunch humanoid_robot_arm_cam.launch
    roslaunch humanoid_aloha_master.launch
    rostopic list
    rosnode list

    conda activate aloha
    python humanoid_one_side_teleop_left.py
    python humanoid_one_side_teleop_right.py

## Components
- Teaser video: Humanoid Black Knight
- Images Carousel
- Youtube embedding: Exoskeleton-style Teleoperation
- Video Carousel
- PDF Poster: Appendix.pdf
- Bibtex citation

## Tips:
- The papers are being organized and the work is over
- Project website： https://humanoid-black-knight.github.io/

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
