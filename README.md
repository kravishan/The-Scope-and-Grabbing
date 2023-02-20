
# The Scope and Grabbing

This is a VR project created as a part of a homework assignment for a course. The objective of the project is to create a magnifying lens and implement a two-handed grabbing system in VR. 


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Features

Part 1: Magnifying Lens

The project is based on the tutorial for creating a magnifying lens, which has been adapted for VR. Instead of animation, the object is made grabbable and attached to the hand. A trigger collider is used to detect if the object is near a hand. The field of view (FOV) of the VR camera cannot be changed, so the "zoom" effect is achieved using render textures.

A rendering layer is used to make an object visible only through the magnifying lens. The project includes one such hidden object, which is marked clearly to indicate its location.

The image on the lens is relative to the viewing angle rather than the orientation of the lens itself. The camera does not rotate with the lens, and instead, the user can see straight through it.

Part 2: Two-Handed Grabbing System

The project includes a novel grabbing system where both hands can manipulate the object simultaneously. The position and rotation changes of the hands are tracked while the object is grabbed, and these combined changes are applied to the grabbed object. This allows multiple hands to manipulate the object simultaneously.



## Installation

To use this Unity project, you will need to have Unity installed on your computer. You can download the latest version of Unity here.

Once you have Unity installed, follow these steps to install the project:

- Clone or download this repository to your local machine.
- Open Unity and click "Open".
- Navigate to the project folder and select the Unity-VR-Assignment folder.
- Unity should load the project automatically. If not, click on the project in the Unity Hub to open it.

That's it! You should now be able to run the project in Unity and build it for your desired platform. If you run into any issues or have any questions, please feel free to reach out.

## Conclusion

This project demonstrates how to create a VR environment in Unity and enable basic interaction and movement using C# scripting. The project can be used as a starting point for more complex VR projects or as a learning tool for those new to Unity and VR development.
## Documentation

[Documentation](https://docs.google.com/document/d/1-mu2BaeNdHf2DCSPiriP8W9TF0yvLGQ_hc4OmX7oWjA/edit#heading=h.omggr5dv7ift)


## Credits

This project was created by Kavindu Ravishan. The tutorial for creating a magnifying lens in VR was used as a reference. The assets used in the project were either provided in the tutorial or download from Unity Asset Store.