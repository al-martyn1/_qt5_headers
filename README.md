This repository allows (if it is supported by IDE) You to simply include Qt header files by Qt type name.
Add "qt_headers" to C++ include search path and then type:

  #include <qt/Q
  
And then Your IDE will suggest a suitable types for You.

Git-hub does not allow you to keep more than 1000 files in one directory, so you have to generate them yourself using umba-make-headers utility.
You can find it at: 

  https://github.com/al-martyn1/umba-make-headers
