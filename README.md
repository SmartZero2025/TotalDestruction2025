# TotalDestruction2025
RTS/ Deep Core Strategy game for WiiU platform, name: Total Destruction 2025: Human Apocalypse

More informations about how this game is programmed now. This game is programmed from scratch!

- nextgen-animation engine will use an own driver (animations.rpl)
- Fully Raytraced (approx. 5 Billion pixel-lights = target). Comes as own driver (Godrays.rpl)
- Nextgen-Soundengine for good vibes. Will use an own driver as well (Sound2025.rpl)
- Nextgen-AI (own custom AI-engine, based on scripting), uses an external driver (AI.rpl)
- physics, like destruction of the ground & battlefield will be running via an external driver as well (physics.rpl & destruction.rpl)

- no constant patches required. No install. finished game will be smaller than guessed in the past (approx. 60-100 mbytes in size only, where the libraries are the biggest part of the game, and assets and the game-files itself (resssources) Will be really small)
- Game will be 100% ARCADE-fun. one of the most-advanced ARCADE-RTS-games ever created!
- touchscreen-support targeted! mouse-support might be possible in future (requires additional driver as well, which could be "touchscreen.rpl" or mouse.rpl)
- resolution will be 720p or 1080p depending on how many ressources will be required for full raytracing (godrays-engine)
- internet-support battle is not planned for now but might be possible in the future with another external driver (internet.rpl).
- Many parts of this game will run on assembler-routines via JAVA-implementation
- features precise realtime-hitboxes. there will be no "bad units" doing stuff what you don´t want (e.g. such as "harvesters" in C&C, where they go into an enemy base since they are dumb as a toaster). each enemy will have it´s own precise hitbox and will only do what you command it to do (will use another driver which is called "hitbox.rpl")

- This game will use a "dummy"-like exe-file (RPX) which will be tiny in size, which is necessary to reach highest possible execution-speed on such an unusual processor and to have native OS-support. And there will be a big main-exe which will come as another driver-file (RPL) to cover all methods, to make sure this game runs like it should run.




