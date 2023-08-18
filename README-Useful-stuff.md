
## Useful Commands

find . -name "*.h" -exec sh -c 'mv "$1" "${1%.h}.hpp"' _ {} \;

to turn all files ending with .h to files ending with .hpp

Command Breakdown:

'.' => search path starting at current directory marked by ' . '

-name => set find match name (in this case all files that end with .gappedPeak)

-exec => execute the following command on every match

sh -c => 'exec' creates an independent shell environment for each match

mv "$1" "${1%.gappedPeak}.bed" => mv first variable (denoted by $1), which is the current file name, to new name. Here I do a substring match and delete; so take first var again, $1 and use % to delete .gappedPeak from the string. The .bed at the end just concatenates the remaining variable, which in the example below would now be testNumber, with .bed, creating the new testNumber.bed filename.

The underscore is a placeholder for $0

The {} is replaced by each (*.gappedPeak) filename found by the find command, and becomes $1 to the sh command.

\; marks the end of the -exec command.  You can also use ';' or ";".

to zip all files beginning with heizlog use this

zip logdec2021.zip heizlog*
