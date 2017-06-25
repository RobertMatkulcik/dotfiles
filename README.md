Ussage of color change to directories...
dircolors -p > .dircolors

>
OTHER_WRITABLE 30;41 # dir that is other-writable (o+w) and not sticky

eval "$(dircolors ~/.dircolors)";

ALSO add the eval command above to your ~/.bashrc file.
