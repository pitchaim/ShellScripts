# ShellScripts
A collection of bash shell scripts for performing various quick functions.

*Started 9/6/2016 (AIM)*

###animateDiffeo
Calls [ffmpeg](https://ffmpeg.org) to create a 50 fps animation of all jpeg files in your directory. Specify source directory, number at end of filename, and output filename (with type extension).
Designed for use with output of a modified version of a Matlab image-scrambling script. Call (from containing directory, e.g.) using following syntax:

        `animateDiffeo <path/to/source/directory> <number> <output_name.filetype>`

###png2jpg   
Calls [sips](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/sips.1.html)
to batch-convert png images to jpeg. Runs from current directory. Call using following syntax:

        `./png2jpg <output_folder_name>`
        

