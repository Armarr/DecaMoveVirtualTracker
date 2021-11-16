# DecaMoveVirtualTracker

Experimental Vive Tracker emulation for DecaMove. It reads the rotation returned by the DecaMove SDK and through some badly written IK code attempts to spawn a Vive tracker near your waist.
It does a bad job right now, mainly the IK is not very accurate. I cannot wrap my head around quaternion transformations and gave up on the project for now.
Some of the IK code was copied from OwoTrack but with more hardcoded values because I was trying to get the basics working before adding the configurability back.

# How to use
Download the repository and just put the folder someplace SteamVR will be able to access and then run driver_install.bat
A new tracker will show up in SteamVR and the position will update while the DecaMove is connected