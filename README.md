# enBask Studios | Tech Demo | Visual Programming
Quick tech demo of a visual programming language for an upcoming project around programmer simulation.

# Download
- [Windows](https://github.com/enBask/PRGTD/raw/master/Windows64.zip)
- [Linux](https://github.com/enBask/PRGTD/raw/master/Linux64.zip)
- [MacOS](https://github.com/enBask/PRGTD/raw/master/macOS.zip)

# How to use
The visual language is node based. You create node by clicking and dragging a node type from the menu on the left onto the canvas. Nodes have IN pins on the left, and OUT pins on the right. You connect IN and OUT pins together between nodes to flow data or execution. Red pins are the execution path of your program, which starts with the "Start" node. Blue pins represent data which will flow as needed during execution. The console log node is used to output data at the moment.

Program execution will execute one step per game frame, so slower computers will execute slower.

# Controls
- Run button at the top will start execution.
 - Turns into a stop button to cancel execution early.
- Clear log will clear the output cancel at the bottom.
- Reset Program will delete all nodes in the canvas (no confirm).
- Mouse wheel scrolls in and out.
- Left mouse hold on canvas to move the camera.
- Left mouse hold on a node to move it around.
- Right click a node to delete it (no confirm)
- Right click a pin to delete the pin connection
- Left click a pin and click a pin on another node to connect (can't connect pins on same node, and IN can only connect to OUT).
- Red pins will only connect to other red pins (execution path).
- Constant nodes are the only way to input data into the system.

# Demo Video
POW(base,exp) function demo
[![POW(base,exp) Function Demo](https://github.com/enBask/PRGTD/raw/master/Capture.PNG)](https://www.youtube.com/watch?v=U-Lhb-PBKlY "POW Function Demo")
