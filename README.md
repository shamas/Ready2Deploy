# Ready2Deploy
A quick collection of scripts I've compiled to put all files into one place prior to copying them to a server. This is mainly useful for small websites with lots of Javascript.

# Usage
This is built to be used in linux
1. Copy the contents to somewhere where you can execute them
2. Edit r2d.config to have the correct directory
3. Edit r2d.files to have the files you wish to include. The wildcard `*` works fine.
4. Run ./r2d

- All your files will be sitting in the $out directory, as defined.
- All occurances of the filenames in the files moved will have been replaced to the directory on the same level.
