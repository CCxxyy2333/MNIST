# MNIST
MNIST dataset mirror / MNIST镜像仓库

#使用方法

用于帮助正在学习《鱼书》/《深度学习入门：基于Python的理论与实现》的同学下载数据集
遇到如下报错：
"urllib.error.HTTPError: HTTP Error 404: Not Found"

这主要是因为dataset/mnist.py脚本的下载链接出问题了 http://yann.lecun.com/exdb/mnist/

##方法1

可以修改脚本中的链接为 https://github.com/CCxxyy2333/MNIST/blob/main/

修改后如下 

url_base = 'https://github.com/CCxxyy2333/MNIST/blob/main/'
key_file = {
    'train_img':'train-images-idx3-ubyte.gz',
    'train_label':'train-labels-idx1-ubyte.gz',
    'test_img':'t10k-images-idx3-ubyte.gz',
    'test_label':'t10k-labels-idx1-ubyte.gz'
}

##方法2
直接下载这四个文件，放在dataset目录下（也就是和mnist.py放在一个文件夹中）
这样再直接脚本，就会跳过下载这个步骤

#其他链接
链接: https://pan.baidu.com/s/1x_i0AqRosc0ALbbCQYVY-A?pwd=6bns 提取码: 6bns 复制这段内容后打开百度网盘手机App，操作更方便哦


















