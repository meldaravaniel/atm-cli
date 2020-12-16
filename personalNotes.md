Steps to use dis:

1) [Install WSL 2](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
1) Follow the rest of the readme. :)
1) ....don't forget that when you change the path var you have to restart the wsl console to have changes take effect. *facepalm*
1) surprise!  you need gcc, otherwise you get an error "linker 'cc' not found".  Run `sudo apt install build-essential`
	* another wrinkle! 404 error during install on amd64 something something.
	* Update the Ubuntu release?? `sudo apt-get update
	* Cool, that appears to have worked...let's try the release build again, shall we?.....
	* YESSSSSSS that worked. nice.`
