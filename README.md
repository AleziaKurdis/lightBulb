# lightBulb
Generate rapidly a visible glowing light source with its light beam for Vircadia.

You only have to adjust the shape, setup the color and user data and the script will manage the material 
and the light entity with no impact on the server since it's all localy rendered for each visitor.

To install:
Import using the “Create” application function:
“Import Entities (.json) From a URL”

Enter this URL:
https://aleziakurdis.github.io/lightBulb/LIGHT_BULB.json

Setup: 
**Light color**: Set the "color" property of the Shape entity, it will determine the color of the light.
**Light Intensity**: Set the userdata "lightIntensity" parameter
**Light beam opening angle**: Set the userdata "lightSpotCutOff parameter
**Light range**: Set the userdata "lightRange" parameter

Restart the client script to have the change effective.

Rotate and position the shape and the light will follow.
