# One-Time Scripts

#####Overview

One-Time scripts start when called upon by a specific radio function or when the user selects them from a contextual menu. They do their task and are then terminated and unloaded. Please note that all persistent scripts are halted during the execution of one time scripts. They are automatically restarted once the one time script is finished. This is done to provide enough system resources to execute the one time script.

##### File Location

Place them anywhere on SD card, the folder /SCRIPTS/ is recommended. The only exception is official model wizard script, that should be put into /SCRIPTS/WIZARD/ folder that way it will start automatically
when new model is created.

##### Lifetime of One-Time scripts

Script is executed when user selects Execute on a script file from SD card browser screen.

Script executes until:
 - it returns value different from 0
 - is forcefully closed by user by long press of EXIT key
 - is forcefully closed by system if if it misbehaves (too long runtime, error in code, low
memory)