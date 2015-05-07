# quadcopter
Github使用过程
1、下载github上的库

git clone https://github.com/minelabwot/quadcopter.git

2、将修改文件拷贝到相应文件夹下

3、在该文件夹下将修改的文件添加到github缓存

git add *(*为所要添加的文件，这个操作要在文件所在文件夹下)

4、添加注释（方便以后对程序做一个了解）

git commit -m ‘…..’ （….为所要做的标示）

5、push一下，同步本地和网上的库

git push


将网上的库和本地同步，pull一下

git pull

查看这次的修改
git status


如果要新建文件夹。

mkdir microduino

touch microduino/README

git add microduino/

git commit -m ‘microduino’

git push
