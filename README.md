# path_stats
Take a path and show the ownership of each part

Every now and then, for reasons, my computer will baulk at allowing me to read or write to a directory. Normaly this is when installing or trying to assess Python or Ruby modules. It all comes down to incorrect permissions being used at some point in the past

But where is the issue? Rather than just spam `chown` until it works run this and it will tell you the owner and group at each part of the path. You can then `chown` the right part
