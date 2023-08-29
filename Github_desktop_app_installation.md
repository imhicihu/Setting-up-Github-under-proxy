### GitHub desktop
![734357948-3c5f7d74-4082-11e5-856c-133cae8d342e.png](images/2951408339-github.png)
* download the desktop client from [Github](https://desktop.github.com/)
	- on [Mac](https://desktop.github.com/)
	- on [Windows](https://desktop.github.com/)
	- on [Linux](https://aur.archlinux.org/packages/github-desktop/)
* verify that you meet the minimal requirements: on Mac OS X 10.9 or later; on Windows Vista or later; on Linux verify this [dependencies](https://aur.archlinux.org/packages/github-desktop/)
* install the desktop client
* before initial run
	- on Mac: 
		- open Terminal
		- in some cases, prompts to install [Xcode command line developer tools](https://developer.apple.com/download/more/): install it
	- on Windows: 
		- press `Win-R`, type `cmd` and press `Enter` to open a command prompt session
		- click `Start`-> `Program Files` -> `Accessories` -> `Command Prompt`
		- click the `Start` button and type `cmd`
		- In some cases, you must choose `Run as Administrator` and click `Yes` to open command prompt session with elevated privileges
	- on Linux: open Terminal
* Type: `git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:8080`
* change parameters accordingly to the "real thing"