#  OpenCV_CrossInstaller

This set of scripts downloads OpenCV, required additional packages, imports python libs from the target board and transfers the cross-compiled library back to the board to be installed.

Launch the script with

    chmod +x fullProcess.sh
    ./fullProcess.sh

and install the compiled library executing, in the target board, 

    sudo rsync -av installation/ /usr/local

For more information visit [http://www.alvaroferran.com/blog/cross-compiling-opencv-for-arm-boards](http://www.alvaroferran.com/blog/cross-compiling-opencv-for-arm-boards)
