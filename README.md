# VSLAM
计算机视觉中的多视图几何

矩阵论

凸优化

概率论沉思录

概率机器人

$ ./Examples/RGB-D/rgbd_tum Vocabulary/ORBvoc.txt Examples/RGB-D/TUM1.yaml sequence_fr1_xyz/rgbd_dataset_freiburg1_xyz/ Examples/RGB-D/associations/fr1_xyz.txt

$ ./Examples/RGB-D/rgbd_rs Vocabulary/ORBvoc.txt Examples/RGB-D/RS-D430.yaml 

Usage: 

$./rgbd_tum path_to_vocabulary path_to_settings path_to_sequence path_to_association

建立一个相应大小的空文件(这里count=3000就是3G啦)：

$cd /

$sudo dd if=/dev/zero of=swapfile bs=1M count=3000

$sudo mkswap /swapfile

$sudo swapon /swapfile

$watch free --mega
