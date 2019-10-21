### Installation
1. Make backups of the following files in the \bin\ folder: vbsp.exe, vrad_dll.dll, vvis_dll.dll

2. Download the files from the Releases page, then copy the files into the \bin\ (replace all the files if you need to)

3. Compile your map as usual

If you didn't make backups of the files and want to revert, you should be able to Verify Integrity of Files through Steam to get the original files back


### Why?
The brush limit is increased by 1.375 times the default value to allow for more brushes in your map. This is for the few that cannot add more into their maps due to brush limits rather than brush side limits

I can't increase the number brush sides as it is hard coded but it is a large . I have increased the brush limit so you can get closer to the real limit of Source

If you go over the face limit, without going over the brush limit, and try running the game then the game will crash rather than failing at the compile stage. Note, I believe there are no error messages if the maximum number of faces are exceeded.

I haven't increased the limit further because else you might go over the face limit without realising, as it is still possible to go over the face limit with about 3% of the brush limit spare using cuboids.

To ensure you are within the limits, check Map > Map Information. Solids refers to the number of brushes in your map.

**The limit is now 11264 brushes (from 8192).** The brush sides limit is already at the maximum, 65536. 


### License
##### SOURCE 1 SDK LICENSE

Source SDK Copyright(c) Valve Corp.  

THIS DOCUMENT DESCRIBES A CONTRACT BETWEEN YOU AND VALVE 
CORPORATION ("Valve").  PLEASE READ IT BEFORE DOWNLOADING OR USING 
THE SOURCE ENGINE SDK ("SDK"). BY DOWNLOADING AND/OR USING THE 
SOURCE ENGINE SDK YOU ACCEPT THIS LICENSE. IF YOU DO NOT AGREE TO 
THE TERMS OF THIS LICENSE PLEASE DON’T DOWNLOAD OR USE THE SDK.  

  You may, free of charge, download and use the SDK to develop a modified Valve game 
running on the Source engine.  You may distribute your modified Valve game in source and 
object code form, but only for free. Terms of use for Valve games are found in the Steam 
Subscriber Agreement located here: http://store.steampowered.com/subscriber_agreement/ 

  You may copy, modify, and distribute the SDK and any modifications you make to the 
SDK in source and object code form, but only for free.  Any distribution of this SDK must 
include this LICENSE file and thirdpartylegalnotices.txt.  
 
  Any distribution of the SDK or a substantial portion of the SDK must include the above 
copyright notice and the following: 

    DISCLAIMER OF WARRANTIES.  THE SOURCE SDK AND ANY 
    OTHER MATERIAL DOWNLOADED BY LICENSEE IS PROVIDED 
    "AS IS".  VALVE AND ITS SUPPLIERS DISCLAIM ALL 
    WARRANTIES WITH RESPECT TO THE SDK, EITHER EXPRESS 
    OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, IMPLIED 
    WARRANTIES OF MERCHANTABILITY, NON-INFRINGEMENT, 
    TITLE AND FITNESS FOR A PARTICULAR PURPOSE.  

    LIMITATION OF LIABILITY.  IN NO EVENT SHALL VALVE OR 
    ITS SUPPLIERS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, 
    INDIRECT, OR CONSEQUENTIAL DAMAGES WHATSOEVER 
    (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF 
    BUSINESS PROFITS, BUSINESS INTERRUPTION, LOSS OF 
    BUSINESS INFORMATION, OR ANY OTHER PECUNIARY LOSS) 
    ARISING OUT OF THE USE OF OR INABILITY TO USE THE 
    ENGINE AND/OR THE SDK, EVEN IF VALVE HAS BEEN 
    ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  
 
       
If you would like to use the SDK for a commercial purpose, please contact Valve at 
sourceengine@valvesoftware.com.