# mesa-20.1.0-linux
mesa , 20.1.0 , linux , vulkan , предупреждаю собирается под патент если вы унесли отсюда это не ваш метод компиляции , а взятый отсюда ибо вы не понимаете что clangcodegen это статическая библиотека , но вы её ни в каноникал ни в арч продукции не сгенерировали вместе с остальными так что , а у меня есть эти библиотеки из другой OS они там сгенерировались и имеют они расширение .a. и прежде чем утаскивать на патреон и похороникс надо давать ссылку.


                                Griggorii@gmail.com commerical patent (cached)

                                                mesa-20.1.0

                 mesa my backend menteined my include generate .build/src special OS_INCLUDE

_________________________________________________________________________________________________________________

$$ Deb download install all llvm-config-10 https://yadi.sk/d/q589eoL97F-C3A

$$ Deb download install ninja-build+meson https://yadi.sk/d/M9-Obbk2zby0uA


$$ sudo apt  update && sudo apt --reinstall install libomxil-bellagio-dev libwayland-egl-backend-dev libunwind-dev libegl1-mesa-dev mesa-common-dev libgles2-mesa-dev libosmesa6-dev libglu1-mesa-dev valgrind valgrind-dbg libxvmc-dev libxcb-dri2-0-dev libxcb-dri3-dev libxcb-glx0-dev libxcb-randr0-dev libxcb-render0-dev libxcb-shape0-dev libxcb-sync-dev libxcb-xfixes0-dev libxcb1-dev libxine2-dev libxatracker-dev -y && sudo apt install libd3dadapter9-mesa-dev llvm clang make -y && sudo apt --reinstall install libgcrypt20-dev libxcb-present-dev python-mako libxshmfence-dev libxext-dev libxdamage-dev libx11-xcb-dev libexpat1-dev libxxf86vm-dev libva-dev libclc-dev libdrm-dev libegl-dev libgbm-dev libgl-dev libgl1-mesa-dev libgles-dev libglvnd-dev libglx-dev libopengl-dev libpthread-stubs0-dev libvdpau-dev libvkd3d-dev libvkd3d-utils1 libvulkan-dev libx11-dev libxau-dev libxdmcp-dev mesa-opencl-icd nvidia-cg-dev -y && sudo apt --reinstall install liblzma-dev libxine2-bin libxcb-shm0-dev libxcb-xv0-dev libxcb-xvmc0-dev meson ninja-build -y && sudo apt --reinstall install libxrandr-dev libzstd-dev libmirwayland-dev wayland-protocols libsensors4-dev xserver-xorg-video-intel -y && sudo apt purge xserver-xorg-video-intel -y && sudo apt --reinstall install libgccjit0 -y && sudo apt --reinstall install libgccjit-9-dev -y && sudo apt --reinstall install libmesa-dev -y

$$ cd ~/

$$ git clone https://github.com/Griggorii/mesa-20.1.0-linux

$$ cd mesa-20.1.0-linux

$$ sudo tar xvpf llvm_include.tar.xz -C /

$$ sudo tar xvpf x86_include.tar.xz -C /

$$ tar xvpf mesa-20.1.0.tar.xz

$$ sudo mkdir /home/griggorii

$$ sudo mv mesa-20.1.0 /home/griggorii

$$ cd /home/griggorii/mesa-20.1.0

$$ sudo ln -s /usr/include/locale.h /usr/include/xlocale.h

$$ sudo rm -rf /usr/lib/gcc/x86_64-linux-gnu/8/include-fixed/bits

$$ sudo rm -rf /usr/lib/gcc/x86_64-linux-gnu/9/include-fixed/bits

$$ sudo rm -rf /usr/lib/gcc/x86_64-linux-gnu/10/include-fixed/bits

$$ sudo ln -s /usr/bin/python3.8 /usr/bin/python

_______________________________________________________________________________________________________________________
             Выберите себе любой из вариантов например old dump variant или установите сразу два варианта
                    https://github.com/Griggorii/Cinnamon-Budgie-Linux-OS-20-based-19.10-Ubuntu-Pop
              | Dump config OS19 build  2255 wayland | Dump config OS8.0 .build 2170 color quality HD
                
   
   Variant dump 1) .build 2170 color best quality hd gamma quality
   
   Variant dump 2) build  2255 wayland fast wayland perfomance
   
$$ sudo ninja -C .build install

$$ sudo ninja -C build install

$$ sudo rm -rf /home/griggorii
_______________________________________________________________________________________________________________________

Problem version meson ? meson.build

$$ meson --reconfigure --prefix=/usr .build

$$ sudo ninja -C .build install

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

Ну , а так код как видите дан казалось бы можно забрать и выдать под каким нибудь шишкиным иваном или дастин геитсом и тут встает вопрос не все машины умеют компилировать надо ещё смочь такую сделать так что я только рад усложненности и хорошей графике , как говориться работать и болтать на кучах форумов это два разных дела и то что там поболтали на каких то закрытых деньго дележных линукс клубах это не значит что выделили деньги именно за этот драивер тому кто работал. Там просто слишком много инклюдов deep learning в чистом виде , инклюды я конечно уже упаковал и пока отложил. На данный момент работа будет над выявлением тиринга , а в линуксе этого полно и не только в mesa , но и в иксах. 
