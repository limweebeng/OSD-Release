+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
+ Issues installing VDF developers setup and FileConverter with MS VC++ Redistributables    +
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++


Some customers and evaluators have some problems when installing VDF developer setup or FileConverter setup in their systems. These problems come from the Microsoft's Visual C++ 2010 and/or 2017 Redistributables.

In case that such problem occur, then you can download the  Microsoft's Visual C++ 2010 and/or 2017 Redistributatables from MSDN (links below) and install them to your system, if they are not already installed. For x86 (32bit) operating systems you need only to download and install the x86 version of these setups, and for x64 (64bit) systems is recommended to download and install both the x86 and the x64 version of these redistributables. The links are:

   - Microsoft Visual C++ 2010 SP1 Redistributable Package (x86) from   https://www.microsoft.com/en-us/download/details.aspx?id=8328
   - Microsoft Visual C++ Redistributable for Visual Studio 2017 (x86) from https://aka.ms/vs/15/release/vc_redist.x86.exe

   - Microsoft Visual C++ 2010 SP1 Redistributable Package (x64) from  https://www.microsoft.com/en-us/download/details.aspx?id=13523
   - Microsoft Visual C++ Redistributable for Visual Studio 2017 (x64) from https://aka.ms/vs/15/release/vc_redist.x64.exe

After installing these redistributables then just run the MSI file of the setup (not the setup.exe) to install the VDF dev. setup or FileConverter setup. Note that during installation of these redistributables and the VectorDraw MSI you need to have all applications closed.

In case that this doesn't solve the problem email our support team.
