# Trash Classification Project

This trash classifier is part of a project that I did for my CS462 project: Internet of Things.

For this project, we wanted to train a ML model that is able to classify materials that can be recycled;
but also be able to recognise things that are trash and should be recycled.

For this project, I'm currently using Edge Impulse to create and train the model. 

A public version is currently hosted at https://studio.edgeimpulse.com/public/58849/latest; feel free to clone that and make changes if necessary.

This version on Github is one that can be run on your own computer. In future, I'm planning to export this project into a Raspberry Pi/Arduino Uno fitted with a camera module, and use that to run the model!



## To run the model & do a live classification: ##

``node run-impulse.js features.txt``

References:
https://docs.edgeimpulse.com/docs/through-webassembly


Testing it on Edge Impulse:  
https://smartphone.edgeimpulse.com/index.html?apiKey=ei_43d756d45b0386fc789cad466204d30415c159d7d60cd9f6588a260a111d4d56

Go to Data Collection Mode -> Testing category if you want to see the live classification on the browser.

Else, just using Classification mode is fine.
