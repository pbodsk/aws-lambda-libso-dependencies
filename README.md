# AWS Lambda libso Dependencies
libso dependencies which can be used in an AWS Lambda layer

## What?
These are the dependencies needed if you would like to use `libso` with an AWS Lambda Layer

I've added both the "raw" dependencies (libportaudio_dependencies) and a zipped version (zipped_dependencies.zip) of them so you can upload that directly.

If you want to make the zip file yourself (in case I forgot something for instance), go to `libportaudio_dependencies` and run

`zip -r ../zipped_dependencies.zip ./*`

And then you can upload that layer to AWS.

Good luck.