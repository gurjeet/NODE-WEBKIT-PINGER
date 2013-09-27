Idea
====

This is still just an idea; nothing concrete yet.

Create an application that uses node-webkit to display the ping times visually on a chart to the user.

I came across npm module `net-ping`, but it failed to compile against the latest nodejs (0.11.5), so I just assumed that the thing is unusable. But then I came across pinger [1] which uses the same package as a dependency, and more importantly, whose Travis builds showed that it (and its dependency `net-ping`) did build successfully against nodejs version 0.10.12.

So, it seems to be usable after all! Possibly a few C++ code edits to make it compatible with latest nodejs may get it to compile it again, and usable in this project.

FWIW, the README of `net-ping` shows that it's a carefully designed package, so I have high hopes of it being a good quality project.

[1] git://github.com/wearefractal/pinger.git
