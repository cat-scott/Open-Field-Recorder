Welcome to the project page for the OFR

# What is OFR:

OFR is the Open Field Recorder created by Invisible Flock (and friends). 

With support and in collaboration with Bournemouth University and Professor Amanda H Korstjens from [LEAP](https://go-leap.wixsite.com/home/amanda-korstjens).

It is an open hardware and software platform for remote long form bio-acoustic recording. 

It is created for *sound artists, conservationists, scientist* and anyone who wants or needs to record audio and environmental data for long periods of time in inhospitable environments. 

It is modular, hackable, meshable and useful in a wide series of situations and applications.

![monkey with REcorder](/images/monkeyRec.jpg)


# Why does it exit:

The OFR was created by Invisible Flock to solve a specific need we had whilst recording large sections of a rainforest in Sumatra. 

We needed recorders that would function in the difficult conditions of the forest for long periods of time in order to monitor the biodiversity of the area and that we could sync together to create large scale multichannel sound installations with audio quality as close to our main field recorders as possible.

The OFR for us was an attempt to bridge a gap that was not currently being fulfilled by other products on the market allowing us to record stereo audio from high quality microphones that were synced via GPS. 

Whilst there are other excellent products that already exist for bio-acoustic monitoring, most notably the [audio-moth](https://www.openacousticdevices.info/), the [solo](https://solo-system.github.io/home.html), and the [swift](https://www.birds.cornell.edu/ccb/wp-content/uploads/2016/09/SWIFT-SD-Card-Formatting-Protocol.pdf) none provided us with the specifics we wanted for this project but you may find they are good fit for you depending on your aims.


# What's inside it:

Expand ability and flexibility were important for us in this design and was the ability for other users to build on it and hack the recorder into their own needs. Version 1.1 is built on the [Spresense](https://developer.sony.com/develop/spresense/) a multicore development board platform by Sony which is programmable via the Arduino IDE.


![exploded view](/images/recorder_fusion.jpg)

# So what can i do with it:

You can record the sound of landscapes in near studio quality for long periods of time day and night in all weather conditions and use GPS and analogue sensors to sync multiple recorders and data readings over time and space.

# Give me some specs:

Version 1.1 of the OFR:


- 2 to 4 channel audio
- 48khz to 198khz audio quality
- time and location sync via GPS to enable meshing of multiple recorders
- sensor logging to sync analogue sensor data points to audio files
- options for multiple budgets and microphone quality (ranging from cheap electrec mics to DPA 4060)
- phantom power 
- theoretical running time of 7 days (dependent on specs used and batteries employed)
- custom shield for extra robustness and direct tangible access to key parameters
- design for inhospitable terrain able to withstand tropical rain storms and sub zero temps


# What are you offering on here:

We do not currently sell the OFR as this would be neither cost effective for us or for you and neither would it be practical for us as we are a small studio whose main output is not product manufacture. 

Instead through this site we are working towards offering the full spec and design files for the OFR, including the CAD files for the box interior, the schematics for the shield, the codebase for creating and running your own version, a software interface for controlling and setting up your recorders and a willingness to engage and share knowledge with you in whatever project you embark on with the OFR.  

This is all provided free (as in both beer and speech) but would appreciate a mention or shoutout as we are hoping to build a community around the creative use of the OFR.

![shield](/images/shieldOFR.PNG)

# How do i use it:

Right now getting a build of your own up and running would require a bit of work on your part but we are here to help with that. In the first instance you will need to head over the [hardware](hardware/hardwareReadme.md) page which lists and explains the next steps. We are working to make the time and effort needed to get you up and running with the OFR system as easy as possible so you can get out in the field with it.

The project and the code is available on the github although at the time of writing we cannot be certain that it is a working version - over the next month we will get all of this documentation up to scratch and ready to flash onto your own OFR system.


# What are the future plans:

Future versions of the OFR will hopefully offer other platforms to run the OFR on as well as provide longer recording time and more i/o options. 

We are currently developing the shield (pictured above) which will increase the OFR's robustness in the field as well as providing physical tangible control over some key parameters of the recorder. We are developing this with our friends at [Digital Nativ](https://www.instagram.com/digitalnativ/) based in Jakarta. We hope that we will be able to offer the shields to  purchase in mid/late 2020. 

We are also working closely with our friend and long time collaborator Romit Raj from design agency [Quicksand](http://quicksand.co.in/) who is working to develop a new ML based detection and bio-auditing system and we hope to be able to release a build of the OFR fine tuned to interface and provide the best possible results with his system. 


# Where is it being used at moment:

The OFR has been deployed in Sumatra in 2019 and will  return there in mid 2020 to help monitor and establish an elephant migration corridor. It is being used in the sate of Karnataka in India where it is similarly being used on farms where human elephant conflict is a recurring issue. Later in 2020 it will be deployed across the North of Finland to record the sound of the yearly freeze as part of an ongoing project with the Sub Zero collective of artists and scientists working on the edge of the artic. Hopefully we can keep this list updated and growing.

# Can i hear what it sounds like:

Yes:
[A loud monkey cackle](/soundSample/cackle-veryloud-box1.wav).
[a storm](/soundSample/THUNDERSTORM-CLIP-BOX8.wav).
[and an orangutan](/soundSample/O-TANG-CLIP.wav).

All of these were recorded in Sumatra in 2019.

# Who else is part of this project:

The OFR was first designed and created as part of a collaboration between Invisible Flock and research undertaken by academics from [LEAP](https://go-leap.wixsite.com/home) specifically Amanda H Korstjens and Helen Slater and their ongoing research through Bournemouth University in the Leuser Ecosystem.

If you have any questions about the OFR, using it, deploying it or anything generally please do not hesitate to get in touch.
