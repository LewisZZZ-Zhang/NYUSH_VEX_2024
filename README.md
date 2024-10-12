# NYUSH_VEX_2024
 For NYU Shanghai Vex team only
    .vscode
        c_cpp_properties.json: Configuration file for C/C++ IntelliSense settings in Visual Studio Code.
        settings.json: General settings for the Visual Studio Code workspace.
        vex_project_settings.json: Specific settings for the VEX project.
    include
        auton-function.h: Header file for autonomous functions.
        autonomous.h: Header file for autonomous mode logic.
        basic-functions.h: Header file for basic robot functions like movement and control (include/basic-functions.h).
        controller.h: Header file for controller-related functions.
        math-tools.h: Header file for mathematical tools and utilities.
        my-timer.h: Header file for timer-related functions.
        parameters.h: Header file defining various constants and parameters used in the project (include/parameters.h).
        PID.h: Header file for PID control logic.
        robot-config.h: Header file for robot configuration and initialization.
        sensors.h: Header file for sensor-related functions.
        vex.h: Header file for VEX-specific definitions and functions.
    src
        auton-function.cpp: Implementation of autonomous functions.
        autonomous.cpp: Implementation of autonomous mode logic.
        basic-functions.cpp: Implementation of basic robot functions like movement and control (src/basic-functions.cpp).
        main.cpp: Main entry point of the program, including user control logic (src/main.cpp).
        math-tools.cpp: Implementation of mathematical tools and utilities.
        my-timer.cpp: Implementation of timer-related functions.
        PID.cpp: Implementation of PID control logic.
        robot-config.cpp: Implementation of robot configuration and initialization (src/robot-config.cpp).
        sensors.cpp: Implementation of sensor-related functions (src/sensors.cpp).
    vex
        mkenv.mk: Makefile environment settings for VEXcode (vex/mkenv.mk).
        mkrules.mk: Makefile rules for compiling and linking the project (vex/mkrules.mk).
    Root Directory
        .DS_Store: macOS system file for storing folder attributes.
        .gitattributes: Git configuration file for handling line endings and file attributes (.gitattributes).
        makefile: Main makefile for building the project (makefile).
        README.md: Project documentation file (README.md).
