### Step 1
		$ cmake.exe CMakeLists.txt
		-- The C compiler identification is GNU 5.3.0
		-- The CXX compiler identification is GNU 5.3.0
		CMake Warning at /usr/share/cmake-3.3.2/Modules/Platform/CYGWIN.cmake:15 (message):
		  CMake no longer defines WIN32 on Cygwin!

		  (1) If you are just trying to build this project, ignore this warning or
		  quiet it by setting CMAKE_LEGACY_CYGWIN_WIN32=0 in your environment or in
		  the CMake cache.  If later configuration or build errors occur then this
		  project may have been written under the assumption that Cygwin is WIN32.
		  In that case, set CMAKE_LEGACY_CYGWIN_WIN32=1 instead.

		  (2) If you are developing this project, add the line

		    set(CMAKE_LEGACY_CYGWIN_WIN32 0) # Remove when CMake >= 2.8.4 is required

		  at the top of your top-level CMakeLists.txt file or set the minimum
		  required version of CMake to 2.8.4 or higher.  Then teach your project to
		  build on Cygwin without WIN32.
		Call Stack (most recent call first):
		  /usr/share/cmake-3.3.2/Modules/CMakeSystemSpecificInformation.cmake:36 (include)
		  CMakeLists.txt:2 (project)


		-- Check for working C compiler: /usr/bin/cc
		-- Check for working C compiler: /usr/bin/cc -- works
		-- Detecting C compiler ABI info
		-- Detecting C compiler ABI info - done
		-- Detecting C compile features
		-- Detecting C compile features - done
		-- Check for working CXX compiler: /usr/bin/c++.exe
		-- Check for working CXX compiler: /usr/bin/c++.exe -- works
		-- Detecting CXX compiler ABI info
		-- Detecting CXX compiler ABI info - done
		-- Detecting CXX compile features
		-- Detecting CXX compile features - done
		-- Configuring done
		-- Generating done
		-- Build files have been written to: /cygdrive/c/Users/iaquij/Desktop/Semester4/open source/cs2963-labs/Lab5


		$ ./tutorial.cxx
		./tutorial.cxx: line 1: //: Is a directory
		./tutorial.cxx: line 7: syntax error near unexpected token `('
		./tutorial.cxx: line 7: `int main (int argc, char *argv[])'


		$ ./tutorial.exe
		-bash: ./tutorial.exe: No such file or directory


		$ ls
		cmake_install.cmake  CMakeLists.txt  tutorial.cxx
		CMakeCache.txt       lab5.md         TutorialConfig.h
		CMakeFiles           Makefile        TutorialConfig.h.in


		$ make
		Scanning dependencies of target Tutorial
		[ 50%] Building CXX object CMakeFiles/Tutorial.dir/tutorial.cxx.o
		[100%] Linking CXX executable Tutorial.exe
		[100%] Built target Tutorial


		$ ./Tutorial.exe
		./Tutorial Version 1.0
		Usage: ./Tutorial number


		$ ./Tutorial.exe 25
		The square root of 25 is 5

### Step 2
		iaquij@iaquijT440s /cygdrive/c/Users/iaquij/Desktop/Semester4/open source/cs2963-labs/Lab5
		$ ls
		cmake_install.cmake  CMakeLists.txt  tutorial.cxx      TutorialConfig.h.in
		CMakeCache.txt       lab5.md         Tutorial.exe
		CMakeFiles           Makefile        TutorialConfig.h
		
		$ cmake.exe CMakeLists.txt
		-- The C compiler identification is GNU 5.3.0
		-- The CXX compiler identification is GNU 5.3.0
		CMake Warning at /usr/share/cmake-3.3.2/Modules/Platform/CYGWIN.cmake:15 (message):
		  CMake no longer defines WIN32 on Cygwin!

		  (1) If you are just trying to build this project, ignore this warning or
		  quiet it by setting CMAKE_LEGACY_CYGWIN_WIN32=0 in your environment or in
		  the CMake cache.  If later configuration or build errors occur then this
		  project may have been written under the assumption that Cygwin is WIN32.
		  In that case, set CMAKE_LEGACY_CYGWIN_WIN32=1 instead.

		  (2) If you are developing this project, add the line

		    set(CMAKE_LEGACY_CYGWIN_WIN32 0) # Remove when CMake >= 2.8.4 is required

		  at the top of your top-level CMakeLists.txt file or set the minimum
		  required version of CMake to 2.8.4 or higher.  Then teach your project to
		  build on Cygwin without WIN32.
		Call Stack (most recent call first):
		  /usr/share/cmake-3.3.2/Modules/CMakeSystemSpecificInformation.cmake:36 (include)
		  CMakeLists.txt:2 (project)

		-- Check for working C compiler: /usr/bin/cc
		-- Check for working C compiler: /usr/bin/cc -- works
		-- Detecting C compiler ABI info
		-- Detecting C compiler ABI info - done
		-- Detecting C compile features
		-- Detecting C compile features - done
		-- Check for working CXX compiler: /usr/bin/c++.exe
		-- Check for working CXX compiler: /usr/bin/c++.exe -- works
		-- Detecting CXX compiler ABI info
		-- Detecting CXX compiler ABI info - done
		-- Detecting CXX compile features
		-- Detecting CXX compile features - done
		-- Configuring done
		-- Generating done
		-- Build files have been written to: /cygdrive/c/Users/iaquij/Desktop/Semester4/open source/cs2963-labs/Lab5

		$ make
		Scanning dependencies of target Tutorial
		[ 50%] Building CXX object CMakeFiles/Tutorial.dir/tutorial.cxx.o
		[100%] Linking CXX executable Tutorial.exe
		[100%] Built target Tutorial
		
		$ ./Tutorial
		./Tutorial Version 1.0
		Usage: ./Tutorial number
		
		$ ./Tutorial 25
		The square root of 25 is 5

### Step 3
		iaquij@iaquijT440s /cygdrive/c/Users/iaquij/Desktop/Semester4/open source/cs2963-labs/Lab5
		$ cmake.exe CMakeLists.txt
		-- The C compiler identification is GNU 5.3.0
		-- The CXX compiler identification is GNU 5.3.0
		CMake Warning at /usr/share/cmake-3.3.2/Modules/Platform/CYGWIN.cmake:15 (message):
		  CMake no longer defines WIN32 on Cygwin!

		  (1) If you are just trying to build this project, ignore this warning or
		  quiet it by setting CMAKE_LEGACY_CYGWIN_WIN32=0 in your environment or in
		  the CMake cache.  If later configuration or build errors occur then this
		  project may have been written under the assumption that Cygwin is WIN32.
		  In that case, set CMAKE_LEGACY_CYGWIN_WIN32=1 instead.

		  (2) If you are developing this project, add the line

		    set(CMAKE_LEGACY_CYGWIN_WIN32 0) # Remove when CMake >= 2.8.4 is required

		  at the top of your top-level CMakeLists.txt file or set the minimum
		  required version of CMake to 2.8.4 or higher.  Then teach your project to
		  build on Cygwin without WIN32.
		Call Stack (most recent call first):
		  /usr/share/cmake-3.3.2/Modules/CMakeSystemSpecificInformation.cmake:36 (include)
		  CMakeLists.txt:2 (project)

		-- Check for working C compiler: /usr/bin/cc
		-- Check for working C compiler: /usr/bin/cc -- works
		-- Detecting C compiler ABI info
		-- Detecting C compiler ABI info - done
		-- Detecting C compile features
		-- Detecting C compile features - done
		-- Check for working CXX compiler: /usr/bin/c++.exe
		-- Check for working CXX compiler: /usr/bin/c++.exe -- works
		-- Detecting CXX compiler ABI info
		-- Detecting CXX compiler ABI info - done
		-- Detecting CXX compile features
		-- Detecting CXX compile features - done
		-- Configuring done
		-- Generating done
		-- Build files have been written to: /cygdrive/c/Users/iaquij/Desktop/Semester4/open source/cs2963-labs/Lab5

		$ make
		Scanning dependencies of target MathFunctions
		[ 25%] Building CXX object MathFunctions/CMakeFiles/MathFunctions.dir/mysqrt.cxx.o
		[ 50%] Linking CXX static library libMathFunctions.a
		[ 50%] Built target MathFunctions
		Scanning dependencies of target Tutorial
		[ 75%] Building CXX object CMakeFiles/Tutorial.dir/tutorial.cxx.o
		[100%] Linking CXX executable Tutorial.exe
		[100%] Built target Tutorial

		$ ./Tutorial 25
		Computing sqrt of 25 to be 13
		Computing sqrt of 25 to be 7.46154
		Computing sqrt of 25 to be 5.40603
		Computing sqrt of 25 to be 5.01525
		Computing sqrt of 25 to be 5.00002
		Computing sqrt of 25 to be 5
		Computing sqrt of 25 to be 5
		Computing sqrt of 25 to be 5
		Computing sqrt of 25 to be 5
		Computing sqrt of 25 to be 5
		The square root of 25 is 5
### Step 4
		$ cmake.exe CMakeLists.txt
		-- The C compiler identification is GNU 5.3.0
		-- The CXX compiler identification is GNU 5.3.0
		CMake Warning at /usr/share/cmake-3.3.2/Modules/Platform/CYGWIN.cmake:15 (message):
		  CMake no longer defines WIN32 on Cygwin!

		  (1) If you are just trying to build this project, ignore this warning or
		  quiet it by setting CMAKE_LEGACY_CYGWIN_WIN32=0 in your environment or in
		  the CMake cache.  If later configuration or build errors occur then this
		  project may have been written under the assumption that Cygwin is WIN32.
		  In that case, set CMAKE_LEGACY_CYGWIN_WIN32=1 instead.

		  (2) If you are developing this project, add the line

		    set(CMAKE_LEGACY_CYGWIN_WIN32 0) # Remove when CMake >= 2.8.4 is required

		  at the top of your top-level CMakeLists.txt file or set the minimum
		  required version of CMake to 2.8.4 or higher.  Then teach your project to
		  build on Cygwin without WIN32.
		Call Stack (most recent call first):
		  /usr/share/cmake-3.3.2/Modules/CMakeSystemSpecificInformation.cmake:36 (include)
		  CMakeLists.txt:2 (project)


		-- Check for working C compiler: /usr/bin/cc
		-- Check for working C compiler: /usr/bin/cc -- works
		-- Detecting C compiler ABI info
		-- Detecting C compiler ABI info - done
		-- Detecting C compile features
		-- Detecting C compile features - done
		-- Check for working CXX compiler: /usr/bin/c++.exe
		-- Check for working CXX compiler: /usr/bin/c++.exe -- works
		-- Detecting CXX compiler ABI info
		-- Detecting CXX compiler ABI info - done
		-- Detecting CXX compile features
		-- Detecting CXX compile features - done
		-- Looking for log
		-- Looking for log - found
		-- Looking for exp
		-- Looking for exp - found
		-- Configuring done
		-- Generating done
		-- Build files have been written to: /cygdrive/c/Users/iaquij/Desktop/Semester4/open source/cs2963-labs/Lab5

		$ make
		Scanning dependencies of target MathFunctions
		[ 25%] Building CXX object MathFunctions/CMakeFiles/MathFunctions.dir/mysqrt.cxx.o
		[ 50%] Linking CXX static library libMathFunctions.a
		[ 50%] Built target MathFunctions
		Scanning dependencies of target Tutorial
		[ 75%] Building CXX object CMakeFiles/Tutorial.dir/tutorial.cxx.o
		[100%] Linking CXX executable Tutorial.exe
		[100%] Built target Tutorial

		$ ./Tutorial 25
		Computing sqrt of 25 to be 5 using log
		The square root of 25 is 5
### Step 5
		iaquij@iaquijT440s /cygdrive/c/Users/iaquij/Desktop/Semester4/open source/cs2963-labs/Lab5
		$ cmake.exe CMakeLists.txt
		-- The C compiler identification is GNU 5.3.0
		-- The CXX compiler identification is GNU 5.3.0
		CMake Warning at /usr/share/cmake-3.3.2/Modules/Platform/CYGWIN.cmake:15 (message):
		  CMake no longer defines WIN32 on Cygwin!

		  (1) If you are just trying to build this project, ignore this warning or
		  quiet it by setting CMAKE_LEGACY_CYGWIN_WIN32=0 in your environment or in
		  the CMake cache.  If later configuration or build errors occur then this
		  project may have been written under the assumption that Cygwin is WIN32.
		  In that case, set CMAKE_LEGACY_CYGWIN_WIN32=1 instead.

		  (2) If you are developing this project, add the line

		    set(CMAKE_LEGACY_CYGWIN_WIN32 0) # Remove when CMake >= 2.8.4 is required

		  at the top of your top-level CMakeLists.txt file or set the minimum
		  required version of CMake to 2.8.4 or higher.  Then teach your project to
		  build on Cygwin without WIN32.
		Call Stack (most recent call first):
		  /usr/share/cmake-3.3.2/Modules/CMakeSystemSpecificInformation.cmake:36 (include)
		  CMakeLists.txt:2 (project)


		-- Check for working C compiler: /usr/bin/cc
		-- Check for working C compiler: /usr/bin/cc -- works
		-- Detecting C compiler ABI info
		-- Detecting C compiler ABI info - done
		-- Detecting C compile features
		-- Detecting C compile features - done
		-- Check for working CXX compiler: /usr/bin/c++.exe
		-- Check for working CXX compiler: /usr/bin/c++.exe -- works
		-- Detecting CXX compiler ABI info
		-- Detecting CXX compiler ABI info - done
		-- Detecting CXX compile features
		-- Detecting CXX compile features - done
		-- Looking for log
		-- Looking for log - found
		-- Looking for exp
		-- Looking for exp - found
		-- Configuring done
		-- Generating done
		-- Build files have been written to: /cygdrive/c/Users/iaquij/Desktop/Semester4/open source/cs2963-labs/Lab5

		$ make
		Scanning dependencies of target MakeTable
		[ 14%] Building CXX object MathFunctions/CMakeFiles/MakeTable.dir/MakeTable.cxx.o
		[ 28%] Linking CXX executable MakeTable.exe
		[ 28%] Built target MakeTable
		[ 42%] Generating Table.h
		Scanning dependencies of target MathFunctions
		[ 57%] Building CXX object MathFunctions/CMakeFiles/MathFunctions.dir/mysqrt.cxx.o
		[ 71%] Linking CXX static library libMathFunctions.a
		[ 71%] Built target MathFunctions
		Scanning dependencies of target Tutorial
		[ 85%] Building CXX object CMakeFiles/Tutorial.dir/tutorial.cxx.o
		[100%] Linking CXX executable Tutorial.exe
		[100%] Built target Tutorial

		$ ./Tutorial
		./Tutorial Version 1.0
		Usage: ./Tutorial number

		$ ./Tutorial 25
		Computing sqrt of 25 to be 13
		Computing sqrt of 25 to be 7.46154
		Computing sqrt of 25 to be 5.40603
		Computing sqrt of 25 to be 5.01525
		Computing sqrt of 25 to be 5.00002
		Computing sqrt of 25 to be 5
		Computing sqrt of 25 to be 5
		Computing sqrt of 25 to be 5
		Computing sqrt of 25 to be 5
		Computing sqrt of 25 to be 5
		The square root of 25 is 5

		$ ctest.exe Tutorial
		    Start 1: TutorialRuns
		1/9 Test #1: TutorialRuns .....................   Passed    0.02 sec
		    Start 2: TutorialUsage
		2/9 Test #2: TutorialUsage ....................   Passed    0.01 sec
		    Start 3: TutorialComp4
		3/9 Test #3: TutorialComp4 ....................   Passed    0.01 sec
		    Start 4: TutorialComp9
		4/9 Test #4: TutorialComp9 ....................   Passed    0.01 sec
		    Start 5: TutorialComp5
		5/9 Test #5: TutorialComp5 ....................   Passed    0.02 sec
		    Start 6: TutorialComp7
		6/9 Test #6: TutorialComp7 ....................   Passed    0.01 sec
		    Start 7: TutorialComp25
		7/9 Test #7: TutorialComp25 ...................   Passed    0.01 sec
		    Start 8: TutorialComp-25
		8/9 Test #8: TutorialComp-25 ..................   Passed    0.02 sec
		    Start 9: TutorialComp0.0001
		9/9 Test #9: TutorialComp0.0001 ...............   Passed    0.01 sec
		100% tests passed, 0 tests failed out of 9
		Total Test time (real) =   0.14 sec