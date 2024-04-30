# Xrp-robot-8608
i think were trying to teach kids about robotics, but they keep learning java


Open up xrp box, follow assembly instructions on website on box

 - Follow assembly, then test robot sensors and drivetrain using included website, experiment with block and python programming (though we'll be using Java in FRC) 
- Follow "getting started with xrp" instructions at docs.wpilib.org and flash your image
- Connect to your xrp wifi with password "xrp-wpilib" and test website http://192.168.42.1:5000
 - Download and install latest wpilib release from wpilib GitHub (2024.3.2 at writing) 
- During wpilib install, install vs code 
- Create new robo rio advanced command template project in java (this is the one you'll be working in)
- Create xrp reference (this is your cheat sheet) 
- Setup driverstation enable = true
- Do a hello world using system.out.println("hello world"); (explain when it will show during boot)
- Instantiation of command controller as well as the underlying hid.
- If button pressed print line if statement
- Register button press for the command structure 
- Print from each button type (trigger, button, bumper pov hat) 
- Boot up Xrpgyro and builtinaccelerometer
- Instantiate onboardIO
- Create a xrpmotor object(hard way or copy)
- Move xrpmotor forward and backwards. 
- Boot up both spark motors and get their encoders. (channels in cheat project or documentation online)
- Move both motors same direction
- get joysticks axis output
- move robot with joystick outputs
- setup hello world command (explain the parts of a command and when your hello world will print)
- Setup default command for drivetrain (at this point may just be two motors)
- Create drivetrain file if advanced, if in robot container teach refactor 
- create differentialdrive and assign the two motors
