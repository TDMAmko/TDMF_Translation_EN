# TDMF_Translation_EN
 Collaboration project to tranlsate The Denpa Men Free into English.
 This project contains an overview of fully translated, partly translated and yet to be translated text files. Keep in mind that this project will expand and does not provide all existing text files as of now. 
 
 It is recommended to read through the provided pdf tutorial in order to be able to properly edit and translate text files. Links for the required tools can be found on the pdf tutorial. Keep in mind that tdmfscripteditor has various commands for different type of text files:

TDMFSCRIPTEDITOR commands

-extract/repack: for all non special .dat files

-extract-old/repack-old: for item names .dat file

-extract-v2/repack-v2: for antenna .dat file

-extract-v3/repack-v3: for stage and island texts

-extract-v4/repack-v4: 2BD17000.dat (EQUIP Effects)

-extract-v5/repack-v5: 4C2BD400.dat (Monster Names)

-extract-v6/repack-v6: 50BEB000.dat (Shop description)

TOOL TO REMOVE PREFIXES IN JSON FILES (<u1000/....):
Use find/replace feature and paste: <[\x00-\x7F\p{L}u]*?>
in find, keep "replace with" empty!
Then click "Replace All"
CREATE A COPY BEFORE DOING THIS!!!

Add a new speech bubble: <1\"\u0000>\n 
(for stage text etc.)
