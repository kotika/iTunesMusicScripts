# iTunesMusicScripts

A couple of specialized iTunes/Music scripts that I used to 
1) save a whole bunch of Folder.jpg files from embedded artwork in an existing iTunes collection, and
2) then push them to a second (newer) collection that lacked most artwork

Usage is:

  mp4saveartwork ~/Music
  mp4moveartwork ~/Music /path/to/newcollection

Requirements:

  {brew|port} install coreutils ffmpeg AtomicParsley

Warning:

  I am not responsible for accidental damage to your computer files that may result: files and directories are overwritten with cowboy overconfidence.
