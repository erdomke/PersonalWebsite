+++
date = "2016-04-05T17:48:34-04:00"
description = ""
keywords = []
title = "Surface Pro 4 Review"
categories = ["Technology"]

+++

**Pros**: The device's small size, sufficient battery life, and tablet capabilities (touch 
screen, stylus, camera, etc.) make this device fun to use during normal operation

**Cons**: DPI scaling issues, crashes when trying to wake the device from sleep, and inconvenient
keyboard layout can lead to frustrations

**Overall**: While the device is full-featured and fun to use, I don't believe it is ready yet for
a casual user who wants something that "just works".

**Context**: I am a software developer who is frequently switching between dozens of applications 
including resource intensive applications such as Visual Studio.  I use the Surface Pro 4 configured
with an i7 processor, 16 Gb of RAM, and a 256 Gb SSD.

<!--more-->

![Surface Pro 4 Detail](/images/SurfacePro4.jpg)

## Form Factor and Peripherals

While the small screen size can make it a touch challenging to use densely laid out applications 
(such as Visual Studio), the ease of portability more than makes up for this.  In fact, the small
size allows me to use the device reasonably comfortably from a workout bike and treadmill; something 
I would never have considered with my old, mammoth laptop.  The touch screen is also surprisingly
useful.  I never thought I would be a "poke-the-screen" person.  However, there are times that I
find this much more convenient then trying to identify where the cursor is and use the mouse pad.

### The Pen

The included surface pro pen is useful for jotting down quick notes and drawings in a place where
you are unlikely to lose them or throw them away.  The OneNote app is particularly useful for this
and is well integrated with the pen.  A single click of the pen's button launches the app to a new
page ready for note-taking.  The pen is a bit more cumbersome to use with non-microsoft apps (such
as Inkscape) where it functions as a simple mouse.  Unfortunately, there is not an official way to 
configure the pen for these applications so that the "select" button and eraser could perform
the appropriate function for these applications.  I was surprised however to discover that I could
hack the pen into useful remote control for PowerPoint using the instructions posted by a 
[Ivan Stambolic](http://stambalab.com/controlling-powerpoint-presentations-on-surface-pro-3-using-only-the-pen/).
While a dedicated device would offer more features, it is nice to be able to use the device I 
already have.

### The Keyboard

While other reviews have complained about the rigidity of previous incarnations of the Surface Pro
Type Cover, the cover that comes with the Surface Pro 4 is quite usable, even on my lap.  My one 
complaint with the cover is the keyboard layout.  As a software developer, I frequently need access 
to both the Home/End keys (for editing text) as well as the Function keys (for running and debugging 
code).  Having to constantly switch between these modes via the `Fn` key can prove annoying.  Also,
the choice to truncate the up and down arrow keys is regrettable as it makes it harder to use these
keys whether for scrolling through a web page, playing a game, or for another purpose.  On the plus
side, the backlighting does make the keyboard easier to use in the dark.

### Docking to External Monitors

![Surface Pro DPI Issues](/images/SurfacePro4_DpiScalingIssues01.png)

One of my biggest frustrations with the Surface early on was getting my docking station set up.  In
particular, I was having problems getting my surface to display on the two monitors on my desk via 
the docking station.  The original mini display port to HDMI connectors I was using functioned 
without issues when connecting my surface to the monitor directly, but would not function via the 
docking station.  I ended up finding that the StarTech #MDP2DVIS would work via my docking station
even though the previous StarTech model did not.

A continuing frustration, though, has been DPI inconsistencies.  The Surface is a high resolution 
device with a native DPI of 192.  My monitors are standard resolution with a DPI of 96.  Because
of this mismatch, there are times where Windows does not know what DPI to render various 
applications at.  (The screenshot above is a single screenshot of three applications side by side.)
As a result, parts (generally not all) of certain applications will appear at half or double their 
correct size.  This can make these applications difficult to use.  I have still not been able to 
concretely identify what causes Windows to render applications one way versus the other.  However, 
it sees more likely that Windows will render applications correctly on my 96 DPI monitors if I boot
up the device while it is docked.

## Battery Life

Much like [observed by others](http://www.techradar.com/reviews/pc-mac/tablets/microsoft-surface-pro-4-1290285/review/3)
the battery life is no where close to the advertised specification of 9 hours of video playback.
Over the last few months of usage, I have gotten much closer to 4 hours on a full charge.  While this
discrepancy is discouraging, I do not recall if I have ever had a standard laptop which supplied
much more than 2 hours of battery life.  As a result, I still find the Surface very useful in this
regards.

## Windows 10

Having skipped Windows 8 in favor of going straight to Windows 10 from Windows 7, I find the 
transition to be fairly painless.  In all of the important ways, the operating system still feels
like Windows 7, and all of the tablet apps and features fit seemlessly into the desktop experience.
The solid state hard drive and ample RAM also make both the operating system and its applications
very quick to load.

## System Stability

![Windows 10 Blue Screen of Death](/images/Windows10Bsod.png)

<em><small>From <a href="http://www.thewindowsclub.com/blue-screen-death-windows-10">The Windows Club</a></small></em>

One of my biggest complaints with my Surface Pro 4 (other than DPI issues) is with system stability.
The device really feels like a step back in terms of reliability.  In the last few months, I have
already had the pleasure of becoming acquainted with the new "blue screen of death" on several 
occassions.  In addition, it is hit or miss whether or not I will be able to get the device to wake
up from sleep.  While I have learned to be somewhat patient with the device (I have gotten it to
wake up from sleep after say 20-30 seconds despite no visual indication on the monitor), there are
still times where I have not been able to wake the device.  The tricks I have discovered are:

1. *Disconnect the device from the docking station.*  Sometimes, the issue is that the Surface has
   stopped communicating with the monitors via the dock.  Disconnecting offers you the
   opportunity to get into the device and save your work before rebooting so that the external
   monitors function again.
2. *The two button reset.*  I have had mixed success with simply holding down on the power button to
   trigger a reboot.  However, holding down on the power and volume up buttons simultaneously
   for approximately 20 to 30 seconds does seem to be reliable.  Simply select `Exit` >
   `Restart Now` at the BIOS screen, and the device should start up again normally.