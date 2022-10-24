# Godot4 Action List
Plugin to add a simple global action list for interactables in Godot 4

![gif showing an action prompt appearing as a player object approaches an interactable object](https://raw.githubusercontent.com/acegiak/Godot4-Action-List/main/screenshots/Recording%202022-10-25%20at%2006.42.45-sm.gif)


To install/use:
 * Unzip folder contents into Godot Project
 * Add QuickActionList.gd as QuickActionList to Autoload in Project Settings
 * Create an Area3d and add Interactable.gd script (add collisionshape child as required)
 * In inspector set Action Label field to the name of the interaction
 * Connect "Execute" signal to a method to run when interaction performed
