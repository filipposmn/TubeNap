{\rtf1\ansi\ansicpg1252\cocoartf2509
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww19380\viewh14620\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 READ ME:\
\
The app is fully functional. \
The app can be run either on Xcode, using the simulator, or on a real device supporting at least iOS 12.4 (so from the iPhone 5s onwards)\
\
\
RUN ON XCODE\'92S SIMULATOR\
\
If you choose to run the app on the simulator, the sound classification algorithm cannot be used because the app doesn\'92t have the required framework for audioProcessing on an Intel processor. For the rest the app works as usual.\
\
\
RUN ON REAL DEVICE\
\
\
If you want to test the app on a real device, please feel free to contact me and I will add your address to the list of verified devices. If instead you own a developer account, please run the app by accessing it.\
Before launching the app you need to follow these steps:\
\
	- uncomment line 40 in CurrentJourney.swift file\
	- uncomment from line 346 to 355 in CurrentJourney.swift file\
	- uncomment from line 401 to 520 in CurrentJourney.swift file\
\
If you are experiencing issues with the libAudioProcessing please refer to this guide (Deployement to Core ML - Sound Classification)\
\
	https://apple.github.io/turicreate/docs/userguide/sound_classifier/export-coreml.html\
}