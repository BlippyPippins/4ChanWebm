4ChanWebm
=========

Create WebM files easily for 4Chan

Basic Usage:

4ChanWebM -i input.mkv -o output.webm -b 00:01:35 -e 30 -t "Title"

Effectively, the above example will pull video from the source file (input.mkv). It will pull a clip starting 1 min 35 seconds into the video and generate 30 seconds of video. It will export that video to output.webm, attaching the metadata title="Title" as well.

For more information on how to use, execute 4ChanWebM -h

For effective use, you MUST declare the -i, -o and -e parameters.
