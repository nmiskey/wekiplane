######
WEKIPLANE - readme and instructions


	REQUIRES:
- Soundplane client software
- Max/MSP 5 or higher
- Java Runtime Environment
- Mac OS Yosemite or later


	TO INSTALL:
Simply copy the "wekiplane" folder to your home directory.


	TO RUN:
Connect your Soundplane and any MIDI controllers you wish to use to control the Wekiplane.
Open the Soundplane client software (distributed free by Madrona Labs).
Double click the "wekiplane.command" file. 


	TO USE:
Listen to the four transformations of FM synthesis parameters by selecting a number with the number box and clicking the blue button.
Click the red button to record a gesture on the Soundplane that you feel closely corresponds with that transformation.
You may record as many examples as you like.
Note that the Wekiplane currently only supports 1-touch gestures on the Soundplane - more touches will be added in later versions.
Once you have recorded examples for all four transformations, click the green button to begin processing Soundplane data.
If the MIDI controller you wish to use is not working, click the "notein" object and make sure your MIDI controller is selected.
By default, the mod wheel on MIDI keyboards controls the volume of the FM synthesis. You can change the device controlling volume by clicking on the "ctlin 1" object and selecting a different device.



	NOTES ON THE WEKIPLANE:
- The more examples of each gesture recorded, the more accurate your gestures will be.
- The Wekiplane works best if each gesture is a single motion that does not involve removing fingers from the Soundplane at any point.
- The more precise you are when recording example gestures - i.e. moving exactly from square to square each time - the more unexpected behaviour will probably result if you deviate from those gestures during runtime. Less precise gestures will be easier to reproduce, but the accuracy of the results will probably be lower.
