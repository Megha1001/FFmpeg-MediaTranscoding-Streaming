# FFmpeg-MediaTranscoding-Streaming

Comprehensive introduction to FFmpeg, media transcoding and streaming

What is FFmpeg
	- Fast Forward Moving Picture Experts Group
	- Open source project
	- Collection of libraries and programs
	- For handline multimedia files and stream
	- Free (GPL/LGPL)



MPEG - It's the alliance of working groups who are behind settin many of the most important being used today, including the MP4 format which we are all familiar with.


Why use FFmpeg
	- Swiss army knife of transcoding/streaming
	- Versatile
	- Fast(written in C with optimazation)
	- Simple
	- Many supported formats(codecs, formats, devices, and protocols)


Who uses FFmpeg?
	- Hundreds of other projects
	- Video platform(YouTube, iTunes)
	- Media players(VLC)
	- Media Asset Management Systems
	- Transcoders
	- Video editors
	- Mobile apps
	- Broadcasters


FFmpeg libraries
	- libavcodec : contains all the encoders and decoders that FFmpeg supports.
	- libavformat : has all the muxers and demuxers to deal with different container formats.
	- libavfilter : Has filter that can be used to modify audio and video as per our requirements.
	- libavdevice : supports different input and output devices.
	- libavutil :
	- libswscale :
	- libswresample :


FFmpeg Tools
	- ffmpeg : Main transcoding engine. Most often invoked from command line or another process.
	- ffplay : Used as a minimal tool for playing audio or video
	- ffprobe : For quickly inspecting media to extract valuable information, like how streams there are in the media or the frame rate of a video etc.


Source
	- No official builds
	- Build from source code(that means you can take hold/look source code and can build on your own)
		- Complex process
	- Pre-build packages
		- if we have package manager(API, Homebrew) - it will take care of installation and its dependencies
	- Build variants
		- Master branch(contains latest bugs fixes) vs release branch
	- Setup procedure
		- Easiest way - setup pre-build packages

DOCUMENTATION LINK
-------------------
https://ffmpeg.org/documentation.html
