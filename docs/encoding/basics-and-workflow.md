# Basics and General Workflow

## Preparation

<todo - downloading a source, looking at the video, some decisions
(resolution(s) for the release, audio codec, group-specific
requirements)>


## Writing the Script

<todo - imports, source filter (mention lsmash, ffms2), examples for resizing,
debanding, AA. with images if possible>


## Encoding the Result

```shell
$ vspipe.exe script.vpy -y - | x264.exe --demuxer y4m --some example --parameters here --output video.264 -
```

```shell
$ vspipe.exe script.vpy -y - | x264.exe --demuxer y4m --some example --parameters here --output video.264 -
```

Editors for VapourSynth usually have inbuilt support for encoding
scripts you wrote. Use `%encode --y4m <clip_variable>` in Yuuno or the GUI
provided by VSEdit.


## Transcoding Audio

<todo - examples for qaac, flac>
