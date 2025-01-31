# tg-copy-coords-to-selected
&#9888; This Python script is now part of the <b>redmaw-tg-toolkit</b> repository, and will no longer be developed as a stand-alone script in this repository.

Click [here](https://github.com/RedMawVFX/redmaw-tg-toolkit) for the redmaw-tg-toolkit repository.<br> 
Click [here](https://github.com/RedMawVFX/redmaw-tg-toolkit/tree/main/scripts/tg-copy-coords-to-selected) to go directly to the <i>tg-copy-coords-to-selected</i> folder in the redmaw-tg-toolkit.
<hr>
Copies valid xyz coordinates from the clipboard to the selected nodes in the active Terragen project. Selected nodes without xyz coordinate parameters are ignored.

### Requirements
Terragen 4 Professional (v4.6.31 or later) <br>
or Terragen 4 Creative (4.7.15 or later) <br>
or Terragen 4 Free (4.7.15 or later) <br>
https://planetside.co.uk/

terragen-rpc <br>
https://github.com/planetside-software/terragen-rpc

### Installation
Install Terragen 4 on your computer. <br>
Install the terragen_rpc module, via the pip install command. <br>
Download this repository via “git clone [repository url]” <br>
Terragen 4 should be running when you run this script. 

In this repository you’ll find two Python scripts, which are identical except for their file extensions.  The file ending in .PY will open a command window when run, while the file ending in .PYW will not.  I recommend using the file with the .PYW extension when the script is run or called from an external file or controller device like a Tourbox.

### Usage
This script has no UI.  In Terragen, copy coordinates to the clipboard by right clicking in the 3D Preview and selecting “<b>Copy Coordinates</b>”.  In the Node Network select the nodes you wish to apply the xyz coordinates to.  Run the script.  The node’s coordinates will be set to the xyz coordinates in the clipboard.

### Reference
terragen-rpc <br>
https://github.com/planetside-software/terragen-rpc

Online documentation for Terragen RPC <br>
https://planetside.co.uk/docs/terragen-rpc/

Blog posts on using Terragen RPC <br>
https://planetside.co.uk/blog/hello-rpc-part-1-scripting-for-terragen/ <br>
https://planetside.co.uk/blog/hello-rpc-part-2-error-handling/ <br>
https://planetside.co.uk/blog/script-it-yourself-kelvin-sunlight-colour-with-terragen-rpc/


