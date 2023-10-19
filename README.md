# Hadoop native lib
*Note*: This repo is still WIP. For now, only the 3.3 branch is being build and the binaries are under artifacts
of each pipeline run. They will be removed after 5 days. When done, they will be permanently found under releases.

This project contains a pipeline that build the native hadoop binaries (winutils.exe and hadoop.dll) for windows. 
When it is finished there should be a release for each hadoop release containing the according binaries
(Probably starting at 3.0.0). 

As the pipeline is publicly viewable and the infrastructure is out of my hand, there is basically no way for me to
poison the binaries. So you shouldn't be worried about downloading virus infected applications. The source is always
the official hadoop github mirror