# Pure and Simple yet Powerful Bounding Box Tool

![PicName](http://ofwzcunzi.bkt.clouddn.com/xFIQaxeKRWNAkdPS.png)
bboxer has the following features:
* drag a box you will see it right on image;
* you can choose class index with number and you can see number on image;
* if you did something wrong, just press r to reset;
* after bouding all box, press s, save all bbox label with normal format.
* all platform can use;
* more...

we are going add more features to this bboxer tool.

![PicName](http://ofwzcunzi.bkt.clouddn.com/IjGwZZL1Y0O3Wv0r.png)
![PicName](http://ofwzcunzi.bkt.clouddn.com/rrwxqpZPNhlhV3YT.png)
# Install
repo contains a cross-platform builded binary program which can be run at **any platform**.
for using:
```
git clone https://github.com/jinfagang/bboxer.git
cd bboxer
mkdir build
cd build
cmake ..
make -j8
sudo make install
./bboxer ~/Documents/images ~/Documents/labels
```
* `~/Documents/images `: is your image contains directory;
* `~/Documents`: is your save bbox lable files directory;

# Announce

all the label file will save into your given dir. and every label file with this format:
```
class_index x_1 y_1 x_2 y_2
```

# Contact
if you have any question when using, please contact me via wechat: `jintianiloveu`, for more my projects, vists my website:
[lewisjin.oschina.io](https://lewisjin.oschina.io)
