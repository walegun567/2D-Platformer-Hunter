# 2D Platformer Controller 
![image](https://github.com/ta-david-yu/2D-Platformer-Hunter/blob/master/Demo.gif)
Implementation of a raycast-based 2D platformer controller in Unity.
Extended from https://youtu.be/MbWK8bCAU2w?list=PLFt_AvWsXl0f0hqURlhyIoAabKPgRsqjz.

# Features

| Feature   | Description |
| --------- | ------- |
| Controllable Jump Height | Player can control the jump height of the controller by releasing the jump input in the middle of jump. |
| On-Slope Movement | Character controller can move on slope stably. User can also setup the max slope angle for each character controller. |
| Air Jump | User can configure how many times a character controller can jump in mid air, or assign a function delegate to determine whether the character can do air jump or not. |
| Wall Jump | Controller is able to perform wall jump and the wall jump force is adjustable. |
| Climbing | User can setup a climbing area that a character controller can enter and move freely inside. The area includes three sub-zone: top, middle, bottom. In top zone, player can enter the area by pressing down input. In other zones, player can enter the area by pressing up input. |
| Restricted Climbing Area | User can restrict the climbing area but still keep the triggerable area. Controller will be smoothly interpolated from triggered position to restricted area on enter. |
| One-Way Platform | Controller is able to fall through one-way platform and move through it. |
| Moving Platform | A platform moving motor that can transport character motor or transform. |
| Dash | User is able to customize dash modules that can be applied to a controller. A dash module describes how a controller moves during a dash action. It can either be a dodging movement or a teleport action. |


# Materials
rvros - Animated Pixel Adventurer
https://rvros.itch.io/animated-pixel-hero
