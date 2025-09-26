# DC03PRO - Mimick iBasso UAC Android application under Windows / Linux / *BSD

## Introduction

The iBasso dongle dacs of the DC series can be controlled via a vendor supplied android application https://play.google.com/store/search?q=ibasso%20uac&c=apps - apart from output volume and stereo balance the following settings can be made:

* gain - three levels low medium high
* "turbo" - on and off, presumably enables or disables output driving opamp
* digital filter - values D1 to D5 

Unfortunately there is no support to access the above device settings under Windows / Linux / BSD operating systems. There simply ist no equivalent to Android UAC app.

The small python application in this repository implements the
above the settings gain, turbo mode and filter.  

## Requirements and platform support

Obviously a python interpreter ist needed to run this little application. 

The details about python version and required modules and libraries can be found here: https://github.com/pyusb/pyusb#requirements-and-platform-support

## Installing

See https://github.com/pyusb/pyusb#installing
