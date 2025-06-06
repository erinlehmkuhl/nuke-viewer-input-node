# nuke-viewer-input-node
reference for how to make a nuke view inport node using .ccc and .cube files

TO USE:
this node should stay in your template and be in every comp.
fill it out with your new .ccc files and such
make a 'viewer' node and go to it's properties
in 'input process' you need to use the name of the viewer input node you made, hopefully it is called VIEWER_INPUT but if it's not, put whatever it is in the knob field
Now the "IP" button at the top of the nuke toolbar area will work. in this newest version i had to click the IP button in the viewer properties and the IP at the top menu bar.

You can click the IP on and off as you need it.
that mostly means ON when working up high in your comp and OFF when looking under the .ccc files near output.


***every time you open a new shot you must click the 'select cccid' button on the front of the gizmo

