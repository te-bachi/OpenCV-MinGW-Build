# OpenCV-4.3.0-x64

```
General configuration for OpenCV 4.3.0 =====================================
  Version control:               unknown
 
  Platform:
    Timestamp:                   2020-05-23T14:58:54Z
    Host:                        Windows 10.0.18362 AMD64
    CMake:                       3.17.1
    CMake generator:             MinGW Makefiles
    CMake build tool:            C:/Qt/Tools/mingw730_64/bin/mingw32-make.exe
    Configuration:               Release
 
  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX AVX2
      requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (16 files):         + SSSE3 SSE4_1
      SSE4_2 (2 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (1 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (5 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      AVX2 (30 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2
 
  C/C++:
    Built as dynamic libs?:      YES
    C++ standard:                11
    C++ Compiler:                C:/Qt/Tools/mingw730_64/bin/g++.exe  (ver 7.3.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Winit-self -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  C:/Qt/Tools/mingw730_64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Wformat -Werror=format-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Winit-self -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         NO
    Extra dependencies:          opengl32 glu32
    3rdparty dependencies:
 
  OpenCV modules:
    To be built:                 calib3d core dnn features2d flann gapi highgui imgcodecs imgproc ml objdetect photo stitching ts video videoio
    Disabled:                    python_bindings_generator python_tests world
    Disabled by dependency:      -
    Unavailable:                 java js python2 python3
    Applications:                tests perf_tests apps
    Documentation:               NO
    Non-free algorithms:         NO
 
  Windows RT support:            NO
 
  GUI: 
    QT:                          YES (ver 5.12.5)
      QT OpenGL support:         YES (Qt5::OpenGL 5.12.5)
    Win32 UI:                    YES
    OpenGL support:              YES (opengl32 glu32)
    VTK support:                 NO
 
  Media I/O: 
    ZLib:                        build (ver 1.2.11)
    JPEG:                        build-libjpeg-turbo (ver 2.0.4-62)
    WEBP:                        build (ver encoder: 0x020f)
    PNG:                         build (ver 1.6.37)
    TIFF:                        build (ver 42 - 4.0.10)
    JPEG 2000:                   build Jasper (ver 1.900.1)
    OpenEXR:                     build (ver 2.3.0)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES
 
  Video I/O:
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (58.54.100)
      avformat:                  YES (58.29.100)
      avutil:                    YES (56.31.100)
      swscale:                   YES (5.5.100)
      avresample:                YES (4.0.0)
    GStreamer:                   NO
    DirectShow:                  YES
 
  Parallel framework:            none
 
  Trace:                         YES (built-in)
 
  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.5.1)
 
  OpenCL:                        YES (no extra features)
    Include path:                C:/opencv-4.3.0/sources/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load
 
  Python (for build):            C:/Program Files/Inkscape/python.exe
 
  Java:                          
    ant:                         NO
    JNI:                         C:/Program Files/Java/jdk1.8.0_211/include C:/Program Files/Java/jdk1.8.0_211/include/win32 C:/Program Files/Java/jdk1.8.0_211/include
    Java wrappers:               NO
    Java tests:                  NO
 
  Install to:                    C:/opencv-4.3.0/release/install
-----------------------------------------------------------------
 
Configuring done
```
