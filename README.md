# IS_PROJECT
Agentic Login Defense System  This is a smart security system that watches how a person logs in, not just what password they use. Instead of being a simple lock, it acts like an agentic observer that can tell the difference between a human and a computer program (bot) in real-time.

Key Features

    1-Live Observation: It acts as an agentic observer, checking typing rhythm and speed in real-time.
    
    2-Risk Scoring: It gives every login attempt a score from 0 to 100 based on how "robotic" the behavior looks.

    3-Automatic Defense: If the risk is high, the system automatically slows down the user or adds extra security steps.
    
    4-Trust System: Good users who log in correctly earn "Trust Points," which makes their future logins easier.
How to Use It

    1-Compile: Run the aiMain.cpp file using a C++ compiler.
    
    2-Login: Try to log in with a username and password from the users.txt file.
    
    3-Check Logs: Open log.txt to see all the behavioral data and security decisions the system made.
Calculations Used

    1-Failure Count: Risk goes up the more times you fail.
    
    2-Attempt Speed: Typing too fast (under 2 seconds) flags the user as a bot.
    
    3-Trust Score: Successful logins reduce your risk score by 2 points for every trust point earned.
