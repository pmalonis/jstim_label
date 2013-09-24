jstim_label
===========

usage: jstim_label [-h] [--overwrite] [files [files ...]]

Label stimulus presentations in arf files, using the output of jstim saved as
a text file.

positional arguments:
  files        List of arf files and corresponding jstim log files. The first
               arf file will be labeled using the first log file, the second
               arf file with the second log, and so on.

optional arguments:
  -h, --help   show this help message and exit
  --overwrite  Overwrites already existing stimulus attributes.
