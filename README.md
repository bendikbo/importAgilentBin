# importAgilentBin
An attempt at an improvement of importAgilentBin function that agilent has implemented in matlab.


# Motivation

Want to read all waveforms in an agilent .bin-file without having the function go through the file once for each waveform you need?
Use this function to do exactly that!

# How to

Just call on this function without any varargin and it automatically acknowledges that you want the entire file content (and not just the first waveform like the previous kinda dumb implementation), you're welcome


# For Agilent people

Hi, I tried to get in touch with you through support_col@agilent.com, but that didn't work, just lemme know (bendik.bogfjellmo@gmail.com) if you want me to take this down. I only wrote it to help a fellow student out, and then I had a thought that this could be usable for a bunch of people. So I threw it up on git.
