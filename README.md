# mesa-20.1.0-linux
mesa , 20.1.0 , linux , vulkan


                                       Griggorii@gmail.com commerical patent (cached)

                                                   mesa-20.1.0

                 mesa my backend menteined my include generate .build/src special OS_INCLUDE

_________________________________________________________________________________________________________________



$$ sudo apt  update && sudo apt --reinstall install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev libglu1-mesa-dev valgrind valgrind-dbg libxvmc-dev libxcb-dri2-0-dev libxcb-dri3-dev libxcb-glx0-dev libxcb-randr0-dev libxcb-render0-dev libxcb-shape0-dev libxcb-sync-dev libxcb-xfixes0-dev libxcb1-dev libxine2-dev libxatracker-dev -y && sudo apt install libd3dadapter9-mesa-dev llvm clang make -y && sudo apt --reinstall install libgcrypt20-dev libxcb-present-dev python-mako libxshmfence-dev libxext-dev libxdamage-dev libx11-xcb-dev libexpat1-dev libxxf86vm-dev libva-dev libclc-dev libdrm-dev libegl-dev libgbm-dev libgl-dev libgl1-mesa-dev libgles-dev libglvnd-dev libglx-dev libopengl-dev libpthread-stubs0-dev libvdpau-dev libvkd3d-dev libvkd3d-utils1 libvulkan-dev libx11-dev libxau-dev libxdmcp-dev mesa-opencl-icd nvidia-cg-dev -y && sudo apt --reinstall install liblzma-dev libxine2-bin libxcb-shm0-dev libxcb-xv0-dev libxcb-xvmc0-dev meson ninja-build -y && sudo apt --reinstall install libxrandr-dev libzstd-dev libmirwayland-dev wayland-protocols libsensors4-dev xserver-xorg-video-intel -y && sudo apt purge xserver-xorg-video-intel -y && sudo apt --reinstall install libgccjit0 -y && sudo apt --reinstall install libgccjit-9-dev -y && sudo apt --reinstall install libmesa-dev -y

$$ cd ~/

$$ git clone https://github.com/Griggorii/mesa-20.1.0-linux

$$ cd mesa-20.1.0-linux

$$ tar xvpf mesa-20.1.0.tar.xz

$$ sudo mkdir /home/griggorii

$$ sudo mv mesa-master /home/griggorii

$$ cd /home/griggorii/mesa-master

$$ sudo ln -s /usr/include/locale.h /usr/include/xlocale.h

$$ sudo ln -s /usr/bin/llvm-config /usr/bin/llvm-config-10

$$ sudo ninja -C .build

$$ sudo ninja -C .build install

$$ sudo rm -rf /home/griggorii
_______________________________________________________________________________________________________________________

Problem version meson ? meson.build

tar xvpf mesa-20.1.0.tar.xz edit meson.build find text editor version replace meson_version : '>= 0.53',

Example 0.46 meson version meson_version : '>= 0.46',

Problem build ?

Example python3.8 not python3.8?

$ sudo ln -s /usr/bin/python3.8 /usr/bin/python

python2.7?

$ sudo ln -s /usr/bin/python2.7 /usr/bin/python

$ sudo rm -rf /usr/lib/gcc/x86_64-linux-gnu/8/include-fixed/bits
$ sudo rm -rf /usr/lib/gcc/x86_64-linux-gnu/9/include-fixed/bits
$ sudo rm -rf /usr/lib/gcc/x86_64-linux-gnu/10/include-fixed/bits

Examle check run folder /usr/lib/gcc/x86_64-linux-gnu/_version_/include-fixed/bits
sudo rm -rf /usr/lib/gcc/x86_64-linux-gnu/........version........./include-fixed/bits

______________________________________________________________________________________

LLVM PROBLEM ?

$$ sudo tar xvpf llvm.tar.xz -C /usr/include/llvm-9

$$ sudo tar xvpf llvm.tar.xz -C /usr/include/llvm-____EXAMPLE___VERSION!

