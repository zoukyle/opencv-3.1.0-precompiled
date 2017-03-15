# opencv-3.1.0-precompiled

# The command to build the project:
1. git clone <opencv>. Then cd opencv, git clone <opencv_contrib>
Note: you should be able to find opencv and opencv_contrib git repo online.

2a. To build on Linux: create a folder 'build'
cd build
cmake -DCMAKE_INSTALL_PREFIX=~/install/opencv \
-DOPENCV_EXTRA_MODULES_PATH=../opencv_contrib/modules \
-DBUILD_opencv_aruco=OFF \
-DBUILD_opencv_bgsegm=OFF \
-DBUILD_opencv_bioinspired=OFF \
-DBUILD_opencv_ccalib=OFF \
-DBUILD_opencv_cnn_3dobj=OFF \
-DBUILD_opencv_contrib_world=OFF \
-DBUILD_opencv_cvv=OFF \
-DBUILD_opencv_datasets=OFF \
-DBUILD_opencv_dnn=OFF \
-DBUILD_opencv_dnns_easily_fooled=OFF \
-DBUILD_opencv_dpm=OFF \
-DBUILD_opencv_face=OFF \
-DBUILD_opencv_fuzzy=OFF \
-DBUILD_opencv_hdf=OFF \
-DBUILD_opencv_line_descriptor=OFF \
-DBUILD_opencv_matlab=OFF \
-DBUILD_opencv_optflow=OFF \
-DBUILD_opencv_phase_unwrapping=OFF \
-DBUILD_opencv_plot=OFF \
-DBUILD_opencv_README.md=OFF \
-DBUILD_opencv_reg=OFF \
-DBUILD_opencv_rgbd=OFF \
-DBUILD_opencv_saliency=OFF \
-DBUILD_opencv_sfm=OFF \
-DBUILD_opencv_stereo=OFF \
-DBUILD_opencv_structured_light=OFF \
-DBUILD_opencv_surface_matching=OFF \
-DBUILD_opencv_text=OFF \
-DBUILD_opencv_tracking=OFF \
-DBUILD_opencv_xfeatures2d=ON \
-DBUILD_opencv_ximgproc=OFF \
-DBUILD_opencv_xobjdetect=OFF \
-DBUILD_opencv_xphoto=OFF \
-DBUILD_opencv_xfeatures2d=ON \
-DBUILD_SHARED_LIBS=OFF \
-DWITH_FFMPEG=OFF \
-DWITH_GTK=OFF -DWITH_GTK_2_X=OFF -DWITH_IPP=OFF -DWITH_IPP_A=OFF \
-DBUILD_ZLIB=OFF \
-DBUILD_TIFF=ON \
-DBUILD_JASPER=ON \
-DBUILD_JPEG=ON \
-DBUILD_PNG=ON \
-DWITH_OPENEXR=OFF \
-DWITH_WEBP=OFF \
-DWITH_OPENCL=OFF \
..

2b. To build on Mac: use CMAKE app. I tried the above cmake command, but it
didn't work.
