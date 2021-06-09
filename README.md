# Building
注意:gazebo要升级到9!

    mkdir build
    cd build
    cmake ..
    make install

## Updating world file

    cd worlds
    erb simple_city.world.erb > simple_city.world


# Running

1. Source setup file

    . [install_prefix]/share/citysim/setup.sh

1. Open world

    gazebo worlds/simple_city.world

![default_gzclient_camera(1)-2021-06-09T21_28_53 498193](https://user-images.githubusercontent.com/57209631/121366990-8205c800-c96c-11eb-9355-fab2356b1281.jpg)

安装完之后,只留下simple_city.world就够了,其他可以删了.

