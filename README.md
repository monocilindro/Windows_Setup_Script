# Mitch's Powershell Setup Script

Why do repetetive tasks when the computer can do them for you?

This simple Powershell script installs [chocolatey](https://chocolatey.org/) and uses choco commands to install my frequently used programs.

This allows me to be up and running quickly on a fresh Windows install.  
Last tested on Windows 10 version 1909.

### Running the script

1) Download and unzip the repository.
2) Open Powershell as an administrator, navigate to the download location.
3) Run the command `Set-ExecutionPolicy Unrestricted` to enable execution of the script.
4) Run `.\setupWindows.ps1`
5) When the setup script finishes, open a new Powershell window (Must be a new window)
6) Run `Set-ExecutionPolicy Unrestricted`
7) Navigate to the directory where the scripts are saved, and run `.\cloneConfigs.ps1`
8) Finally, run `Set-ExecutionPolicy RemoteSigned`. Done!

### TODO

* Streamline the Set-ExecutionPolicy commands that the user must input manually
* Find a way around the git issue so that the scripts can be combined