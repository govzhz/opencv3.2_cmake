## opencv3.2-CMake下载包使用说明

在CMAKE过程中有很多包无法下载或者下载速度奇慢，所有包可以从这里获取

### ippicv_linux_20151201

```
opencv-3.2.0/3rdparty/ippicv/downloads/linux-808b791a6eac9ed78d32a7666804320e
```

### protobuf-cpp-3.1.0.tar.gz

```
opencv_contrib-3.2.0/modules/dnn/.download/bd5e3eed635a8d32e2b99658633815ef/v3.1.0/
```

### xfeatures

该路径下有多个文件需要下载，所有文件都要存放到

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/<file_md5sum>
```

所以这里已经上传了.download文件夹，最简单的方法就是将该文件夹覆盖上述路径的文件夹。否则需要将以下是每个文件一一放入：

#### vgg_generated_48.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/e8d0dcd54d1bcfdc29203d011a797179
```

#### vgg_generated_64.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/7126a5d9a8884ebca5aea5d63d677225
```

#### vgg_generated_80.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/7cd47228edec52b6d82f46511af325c5
```

#### vgg_generated_120.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/151805e03568c9f490a5e3a872777b75
```

#### boostdesc_bgm_hd.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/324426a24fa56ad9c5b8e3e0b3e5303e
```

#### boostdesc_binboost_064.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/202e1b3e9fec871b04da31f7f016679f
```

#### boostdesc_binboost_128.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/98ea99d399965c03d555cef3ea502a0b
```

#### boostdesc_binboost_256.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/e6dcfa9f647779eb1ce446a8d759b6ea
```

#### boostdesc_bgm_bi.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/232c966b13651bd0e46a1497b0852191
```

#### boostdesc_bgm.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/0ea90e7a8f3f7876d450e4149c97c74f
```

#### boostdesc_lbgm.i

```
opencv_contrib-3.2.0/modules/xfeatures2d/cmake/.download/0ae0675534aa318d9668f2a179c2a052
```



