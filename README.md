4ChanWebm
=========

Create WebM files easily for 4Chan

Basic Usage:

4ChanWebM -i input.mkv

Effectively, the above command will create a webm defaulting all values to defaults. The result will be a file named "out.webm", which will reside in the current path. The video's resolution will be 360p, it will be limited to 3MB's, it will record 45 seconds of video starting from the beginning. The encoder will use 4 slices with 16 lag-in-frames and use 2 threads for the encoding. If there is a subtitle file with the same filename as the source file with a .ass extension, it will burn the subtitles to the video as well. The default author and title will be added to the metadata of the video. "(bp) Encoded for 4Chan".

For more information on how to use, execute 4ChanWebM -h to see more advanced options.

4ChanWebM is merely a script which is a wrapper for FFMpeg which requires the libass library enabled.
