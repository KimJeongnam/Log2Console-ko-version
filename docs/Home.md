## Project Description
Log2Console is a development tool offering a nice UI to display, filter and search log messages from different logging services: Log4Net, Log4j and NLog. It can directly receive log events locally or remotely, or read them from a log file... It is written with C#.

_**Note:** Your feedback is always welcome ([Discussions](http://www.codeplex.com/log2console/Thread/List.aspx))._
## Main Features
* View Remote Log Events: use a concept similar to Chainsaw Receivers.
* Fully Customizable and Persistent Preferences (UI and Settings) per Windows Profile.
* Dynamic Filtering, Grouping, Cycling and Searching.
* Multiple Receiver suppport (since v1.1).
* Windows 7 support: Taskbar icons (pause, disable autoscroll, clear all) and Taskbar progress (when messages are received).
* Requires .NET Framework 2.0 only.

## Receivers
* File (Standard log or using log4j xml format)
* UDP IP v4 and v6 (Provides compatibility with log4j and [NLog](NLog))
* .NET Remoting (Prefered receiver for log4net)
* WinDebug (Receiver for OutputDebugString(), in C++)
* MSMQ (Microsoft Message Queuing)
* EventLog (Windows Event Log)
* TCP IP v4 and v6 (primarily NLog for Silverlight)
* Silverlight Socket Policy (clientaccesspolicy.xml)

## Screenshots
_**More [Screenshots](Screenshots) here**_

![](Home_Log2Console_3.png)

