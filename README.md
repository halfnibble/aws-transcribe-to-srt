# AWS Transcribe To SRT

> Create SRT files from AWS Transcribe output.

## Overview
This repository contains code for SRT subtitle creation, originally described in the AWS blog post [“Create video subtitles with translation using machine learning”](https://aws.amazon.com/blogs/machine-learning/create-video-subtitles-with-translation-using-machine-learning/). This repo has been forked from AWS's [aws-transcribe-captioning-tools](https://github.com/aws-samples/aws-transcribe-captioning-tools) repo, and future development is being done by Artiflix.


## Background

Head on over to this blog post to see the instructions to create captions with AWS Transcribe in the SRT format, create alternate language SRT files with AWS Translate, and use AWS Polly to create alternate language video files:
https://aws.amazon.com/blogs/machine-learning/create-video-subtitles-with-translation-using-machine-learning/


## Commands

If you just want to create an SRT or a VTT file, the tools directory contains Python code to convert AWS Transcribe JSON to an SRT or a VTT file. These files can be imported and used on web or desktop video players. 

```shell
python srt.py output_file_from_transcribe.json
```


| name | description | 
|-------|-------------|
|srt.py | Takes the JSON response from AWS Transcribe and converts to a captions.srt file |
|vtt.py | Takes the JSON response from AWS Transcribe and converts to a captions.vtt file |


## License Summary

MIT.
