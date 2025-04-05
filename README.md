# Install RV Image with Scoop

[RV Image](https://github.com/bertiqwerty/rvimage) is a Remote Viewer for Images and annotation tool. [Scoop](https://scoop.sh/) is a command-line installer for Windows. If you have Scoop installed you can run 

```
scoop bucket add rvimage https://github.com/bertiqwerty/rvimage-scoop-bucket
scoop install rvimage
```
and start RV Image with the command
```
rvimage
```

## Update RV Image

With
```
scoop update
scoop update rvimage
```
you get the latest released version.

## Install Scoop

Scoop can be installed with Powershell 5.1 or later via
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
from the prompt `PS C:\>`. Scoop does not need administration rights. See the [Scoop website](https://scoop.sh/) for more details. 
