# Synthesis-Copilot-Builds
Synthesis Copilot allows users to quickly write autonomous code for the FRC game using a user interface

Clicking on a robot position that is on the field will copy the Pose2d to your clipboard, where you can paste it into your code.
![image](https://user-images.githubusercontent.com/45080742/160005191-2304ded9-9c47-4c9f-a69b-dde9d235ef4f.png)

-Click +Robot Position to add a new robot position on the field.
-Automatically copy the robot position you click to your clipboard
-In the format (x, y, rotation in degrees)

To convert to Pose2d:
-Use this function converter by doing i.e: getPose(7.57, 1.79, -88.42) to obtain a Pose2d:

    public static Pose2d getPose(double x, double y, double rot){
            return new Pose2d(x, y, new Rotation2d(Math.toRadians(rot)));
    }
