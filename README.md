
 - 
# What is OFR:

OFR is the Open Field Recorder created by Invisible Flock (and friends). 

It is a open hardware and software platform for remote long form bio-acoustic recording. 

It is created for *sound artists, conservationists, scientist* and anyone who wants or needs to record audio and environmental data for long periods of time in inhospitable environments. 

It is modular, hackable, meshable and useful in a wide series of situations and applications.

![monkey with REcorder](/images/monkeyRec.jpg)


# Why does it exit:

The OFR was created by Invisible Flock to solve a specific need we had whilst record large sections of a rain forest in Sumatra. 

We needed recorders that would function in the difficult conditions of the forest for long periods of time in order to monitor the biodiversity of the area and that we could sync together to create large scale multichannel sound installations with audio quality as close to our main field recorders as possible.

The OFR for us was an attempt to bridge a gap that was not currently being fulfilled by other products on the market allowing us to record stereo audio from high quality microphones that were synced via GPS. 

Whilst there are other excellent products that already exist for bio-acoustic monitoring, most notably the [audio-moth](https://www.openacousticdevices.info/), the [solo](https://solo-system.github.io/home.html), and the [swift](https://www.birds.cornell.edu/ccb/wp-content/uploads/2016/09/SWIFT-SD-Card-Formatting-Protocol.pdf) none provided us with the specifics we wanted for this project but you may find they are good fit for you depending on your aims.


# What's inside it:

Expand ability and flexibility were important for us in this design and was the ability for other users to build on it and hack the recorder into their own needs. Verion 1.1 is built on the [Spresense](https://developer.sony.com/develop/spresense/) a multicore development board platform by Sony which is programmable via the Arduino IDE.


![explodded view](/images/recorder_fusion.jpg)


# Give me some specs:

Version 1.1 of the OFR:


- 2 to 4 channel audio
- 48khz to 198khz audio quality
- time and location sync via GPS to enable meshing of multiple recoders
- sensor logging to sync analogue sensor data points to audio files
- options for multiple budgets and microphone quality (ranging from cheap electrec mics to DPA 4060)
- phantom power 
- theoretical running time of 7 days (dependent on specs used and batteries employed)
- custom shield for extra robustness and direct tagible access to key parameters
- design for inhospitable terrain able to withsatnd tropical rain storms and sub zero temps


# What are you offering on here:

We do not currently sell the OFR as this would be neither costs effective for us or for you and neither would it be practical for us as we are a small studio whose main output is not product manufacture. 

Instead through this site we are working towards offering the full spec and design files for the OFR, including the CAD files for the box interior, the schematics for the shield, the codebase for creating and running your own version, a software interface for controlling and setting up your recorders and a willingness to engage and share knowledge with you in whatever project you embark on with the OFR.  

This is all provided free (as in both beer and speech) but would appreciate a mention or shoutout as we are hoping to build a community around the creative use of the OFR.

![shield](/images/shieldOFR.PNG)

# What are the future plans:

Future versions of the OFR will hopefully offer other platforms to run the OFR on as well as provide longer recording time and more i/o options. 

We are currently devevloping the shield (pictured above) which will increase the OFR's robustness in the field as well as providing physical tangilbe control over some key parameters of the recroder. We are devevlopping this with our friends at [Digital Nativ](https://www.instagram.com/digitalnativ/) based in Jakarta. We hope that we will be able to offer the shields to  purchase in mid/late 2020. 

We are also working closely with our friend and long time collaborator Romit Raj from design agency [Quicksand](http://quicksand.co.in/) who is working to devevlop a new ML based detection and bio-auditing system and we hope to be able to realease a build of the OFR fine tuned to inteface and provide the best possible results with his system. 


# Where is it being used at moment:

The OFR has been deployed in Sumatra in 2019 and will  return there in mid 2020 to help monitor and establish an elephant migration corridor. It is being used in the sate of Karnataka in India where it is similarly being used on farms where human elephant conflict is a recurring issue. Later in 2020 it will be deploeyd accross the North of Finland to record the sound of the yearly freeze as part of an ongoing project with the Sub Zero collective of artists and scientists working on the edge of the artic. Hopefully we can keep this list updated and growing.



