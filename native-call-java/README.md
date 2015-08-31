javac Sample2.java 

gcc     -I/home/ywm/ProgramFiles/jdk1.6.0_45/include/ -I/home/ywm/ProgramFiles/jdk1.6.0_45/include/linux -L/home/ywm/ProgramFiles/jdk1.6.0_45/jre/lib/amd64/server    -L/home/ywm/ProgramFiles/jdk1.6.0_45/jre/lib/amd64/  Sample2.c -ljvm

LD_LIBRARY_PATH=/home/ywm/ProgramFiles/jdk1.6.0_45/jre/lib/amd64/server ./a.out 


Reference By: http://stackoverflow.com/questions/16860021/undefined-reference-to-jni-createjavavm-linux


