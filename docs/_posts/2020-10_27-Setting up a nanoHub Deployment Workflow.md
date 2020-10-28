 ##Cloning Repositories on nanoHUB
 
 In order to test potential applications on nanoHUB it is necessary to establish a process or workflow that includes the target platform.  
 This post will describe a simple procedure for cloning repositories from GitHub on nanoHUB using the nanoHUB workspace.
 
 Launch the workspace tool and open an xterm as follows:  
 1. Visit https://nanohub.org/tools/workspace
 2. Launch the tool
 3. Use the Hub 0 start button on the lower left to open an xterm
 
 The basic procedure described here is to use a terminal within the nanoHUB workspace to clone to the nanoHUB filesystem.  
 Note that this can alos be done using any ssh terminal connection to `somebody@nanohub.org`
 
 1. Open an xterm in the workspace, it will look like this:
 <img width="625" alt="Screen Shot 2020-10-28 at 8 26 57 AM" src="https://user-images.githubusercontent.com/12611210/97442134-80b0ef00-18f7-11eb-8a0a-9b5dfcfa376d.png">  
 2. Visit the repo you want to clone and copy the url:  
 <img width="366" alt="Screen Shot 2020-10-28 at 8 37 05 AM" src="https://user-images.githubusercontent.com/12611210/97443359-ec478c00-18f8-11eb-97a4-3746cf24cf8a.png">  
 3. Return to the xterm and add the URL (note you will need to type it if using the xterm in the workspace tool
 as it is not possible to cut-n-past into that web app.  Using a ssh terminal is preferred here.).  The command should look like:  
 `git clone https://github.com/nanoMFG/toolstart-jupyter.git`  
 
