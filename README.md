# Eovim-theme
ever wanted to hack you eovim theme ?

   well here a template
	 
clone this file then edit the files then

here how to compile your theme if you dont want to digg the man page

$ edje_cc -sd ./snd theme.edc -id ./img

the *theme.edc can be changed to your liking since it the output file!

The other file in the folder should be kept as there "name" or the compiler 

will throw some errors 

after you want to find the location of you theme folder
to find the path of your eovim/theme you can try to do
$ eovim -t Test
it will throw and error and will also show a path that look like 
part of the error will look like that:

failed to set edje file '/usr/share/eovim/themes/(nameofyourtheme)

"usr/share/eovim/themes" copy/past your compiled verion of your theme at tha location.

to use and test your theme  

$ eovim -t (*name) without the edj at the end or it will throw error

you might nead to run that command as a sudoer 
