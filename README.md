4ChanWebm
=========

Create WebM files easily for 4Chan

Basic Usage:

4ChanWebM -i input.mkv -o output.webm -b 00:01:35 -e 30 -t "Title"

Effectively, the above example will pull video from the source file (input.mkv). It will pull a video clip clip without audio starting at 1 min 35 seconds into the video and generate 30 seconds of video. It will export that video to output.webm, attaching the metadata title="Title" as well. If there is a subtitle file with the same filename as the input file (ex: input.ass) it will hard-code those subtitles into the final video as well.

For more information on how to use, execute 4ChanWebM -h to see more advanced options. FFMpeg with the libass library enabled is required for 4ChanWebM to work.

For effective use, you MUST declare the -i, -o and -e parameters. The -e parameter is required otherwise it cannot properly determine the bitrate for the resulting video.
