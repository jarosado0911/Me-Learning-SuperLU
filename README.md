# Me-Learning-SuperLU
This is my attempt to using superlu
I used MINGW64 run as administrator, I did this also in powershell administrator
Using CMake build system. 
   You will need to create a build tree from which to invoke CMake.

   From the top level directory, do:
     	mkdir build ; cd build
   	cmake ..

you may need to add gfortran to the environment variables in windows

execute 

cmake .. -G "MinGW Makefiles"

mingw32-make 

mingw32-make install