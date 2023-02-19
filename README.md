# RWeigelt/DirectShow.Net

A fork of [DirectShow.Net](https://sourceforge.net/projects/directshownet/) version 2.1 (released February 22, 2010) which was published on [SourceForge](https://sourceforge.net/projects/directshownet/files/DirectShowNET/v2.1/) under the Lesser General Public License Version 2.1. 

**This fork is not planned to be a general-purpose enhancement of the original libary**. The purpose of this fork is to make just enough changes so that I can compile the library for use in my C#/.NET 6/WPF projects.

As I plan to distribute my software at some point in the future, the LGPL license requires me to 
* ship the library as an individual DLL (which is the output of this Visual Studio project), and
* make the source code available publicly (which is the purpose of this repository).

I only need a very small subset of the functionality for my purposes ([accessing webcam settings](https://weblogs.asp.net/rweigelt/how-to-access-webcam-properties-from-c)). Please note that I did not perform any tests of features that go beyond that.

**2021-02-04**: I wrote [an article about this fork](https://weblogs.asp.net/rweigelt/compiling-directshow-net-for-use-in-net-5) on my blog. 

**2023-02-19**: Updated to .NET 6. Next update planned for .NET 8.
