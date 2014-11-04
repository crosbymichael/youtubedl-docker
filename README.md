See [youtube-dl](http://rg3.github.io/youtube-dl/) for more details.

The workdir is set to `/download` os if you want to get the output in your current dir just run.

`docker run -v $(pwd):/download crosbymichael/youtubedl "https://www.youtube.com/watch?v=Nw42q1ofrV0"`
