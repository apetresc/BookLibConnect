# Book Lib Connect
A standalone Audible downloader and decrypter

![](res/mainwnd.png?raw=true)

![](res/libwnd.png?raw=true)

Book Lib Connect is an Audible downloader app. It should be seen as temporary/preview project, because its features will become an integrated component in future AAX Audio Converter 2.

_**Note:** Books downloaded with Book Lib Connect and exported for [AAX Audio Converter](https://github.com/audiamus/AaxAudioConverter) do not need a classic activation code. If AAX Audio Converter asks or one, any dummy code will do._ 

## Features
- **Free** and **Open Source** software. 
- Direct download from the Audible server.
- Sign-in via standard web browser to register a _device_, app will not see user’s credentials.
- List your book library and select titles for download.
- Download your books and convert to plain .m4b files.
- Detailed progress monitoring.
- Optionally export as .aax files for [AAX Audio Converter 1](https://github.com/audiamus/AaxAudioConverter) compatibility.
- User guide included.


## Download
Windows setup package version 0.2, English, with manual:

**[BookLibConnect-0.2-Setup.exe](https://github.com/audiamus/BookLibConnect/releases/download/v0.2/BookLibConnect-0.2-Setup.exe)**

## Feedback
Use the [Discussions](https://github.com/audiamus/BookLibConnect/discussions) and [Issues](https://github.com/audiamus/BookLibConnect/issues) sections. 
Be cautious with uploading log files to these sections as they may contain sensitive data.   

## Dependencies
AAX Audio Converter will run on Windows 64bit. Minimum Windows version is 7.
The application requires .Net 5 64 bit to be installed. On Windows 10 systems this should normally be the case, if the system is kept up to date.
If not, the app will prompt you for downloading .Net 5 and open the link in your default web browser. From the many options, pick 
**.Net 5 Runtime x64 for Windows desktop**.

## Acknowledgments
- [mkb79](https://github.com/mkb79/Audible) for his Python library which served as the reference implementation of the Audible API to me, straightforward and easy to follow. 
- [Mbucari](https://github.com/Mbucari/AAXClean) for his Audible decryption library in C#. While recent FFmpeg releases can also do it, it is much more convenient to have an in-process solution.
- [rmcrackan](https://github.com/rmcrackan/AudibleApi) for _the other_ C# implementation of an Audible client library, absolutely worth the occcasional side glance.


## Anti-Piracy Notice
Note that this software does not ‘crack’ the DRM or circumvent it in any other way. The application applies account and book specific keys, retrieved directly from the Audible server via the user’s personal account, to decrypt the audiobook in the same manner as the official audiobook playing software does. 
Please only use this application for gaining full access to your own audiobooks for archiving/conversion/convenience. De-DRMed audiobooks must not be uploaded to open servers, torrents, or other methods of mass distribution. No help will be given to people doing such things. Authors, retailers and publishers all need to make a living, so that they can continue to produce audiobooks for us to listen to and enjoy.

(*This blurb is borrowed from https://github.com/KrumpetPirate/AAXtoMP3 and https://apprenticealf.wordpress.com/*). 