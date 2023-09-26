# VirtualMouse

The aim of this project is to recognise and trigger mouse actions based on the user's gestures.

## Installation
All libraries can be installed using pip or anaconda

## Libraries Used
OpenCV - To capture real-time video of the user 
MediaPipe - For recognising hand gestures based on 21 hand-knuckle coordinates
AutoPy, Pyautogui - To trigger mouse actions

## Actions
Description                                                          Action
Index finger up (on left or right hand.)
All other fingers closed.                                        Cursor Movement

Index and middle fingers up (on left or right hand.) 
All other fingers closed.                                          Left Click

Index, Middle and Ring fingers up (on left or right hand.)
Little and Thumb fingers closed.                                   Right Click

All fingers up except the thumb (on the left or right hand.)        Scrolling 

## Execution
Run python3 MouseControl.py
