# matlab-not-opening
matlab wont opening or starting or live editor dont work
___________________________________________________________________________________________________________________________________
extract matlab to a folder. after unzip go to matlab foldr bin/glnxa64 and delet these file
libfreetype.so.6 exclude/
 libfreetype.so.6.16.0
 
 
 if you have install the matlab and the programm doesent open 
 or 
 if the program opens snd live script doesent work open the termial and paste these
 
_____________________________________________________________________________________________________________________________________  
cd <matlab installer root directory>
cd bin/glnxa64
ls | grep libfreetype
mkdir exclude
mv libfreetype.so.6 exclude/
mv libfreetype.so.6.16.0 exclude/
