# Alfred workflow: Scrcpy
Easy way to display and control (mirror) your Android device connected on USB (or over TCP/IP). 

# Requirements
- Alfred
- Alfred Powerpack
- Android SDK
- Scrcpy from Genymobile

## Installation

### Scrcpy from Genymobile
First you need to install scrcpy from Genymobile:

The application is available in [Homebrew]. Just install it:

[Homebrew]: https://brew.sh/

```bash
brew install scrcpy
```

You need `adb`, accessible from your `PATH`. If you don't have it yet:

```bash
brew cask install android-platform-tools
```

More info: [here](https://github.com/Genymobile/scrcpy)

### Github

1.  Download the [**scrcpy.alfredworkflow**](scrcpy.alfredworkflow) file.
2.  Double click to install

### Packal

1.  Download the **.alfredworkflow** file from [Packal](http://www.packal.org/workflow/scrcpy).
2.  Double click to install

## How to configure
See below how to set the PATH:
![How to configure](images/config.gif?raw=true "How to configure")

**PATH:** _/bin:/usr/bin:/Users/zhenleiji//Library/Android/sdk/platform-tools_

# Usage
See below how to launch scrcpy:
![How to use](images/demo.gif?raw=true "How to use")

# License
	Copyright 2020 Zhenlei Ji

	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at

	    http://www.apache.org/licenses/LICENSE-2.0

	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissions and
	limitations under the License.
