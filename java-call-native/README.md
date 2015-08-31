javac Sample1.java
javah Sample1
gcc   -o libSample1.so  -shared -fPIC    -I/home/ywm/ProgramFiles/jdk1.6.0_45/include/ -I/home/ywm/ProgramFiles/jdk1.6.0_45/include/linux Sample1.c
java Sample1
