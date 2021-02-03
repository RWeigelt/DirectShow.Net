# RWeigelt/DirectShow.Net

A fork of [DirectShow.Net](https://sourceforge.net/projects/directshownet/) version 2.1 (released February 22, 2010) which was published on [SourceForge](https://sourceforge.net/projects/directshownet/files/DirectShowNET/v2.1/) under the Lesser General Public License Version 2.1. 

**This fork is not planned to be a general-purpose enhancement of the original libary**. The purpose of this fork is to make just enough changes so that I can compile the library for use in my C#/.NET 5/WPF projects.

As I plan to distribute my software at some point in the future, the LGPL license requires me to 
* ship the library as an individual DLL (which is the output of this Visual Studio project), and
* make the source code available publicly (which is the purpose of this repository).

I only need a very small subset of the functionality for my purposes (accessing webcam settings as described in [this blog post](https://weblogs.asp.net/rweigelt/how-to-access-webcam-properties-from-c)). Please note that I did not perform any tests of features that go beyond that.