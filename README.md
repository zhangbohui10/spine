# LibgdxTextureView

Libgdx use TextureView Rendering，修改Libgdx的渲染View为TextureView，可以跟原生的view进行透明层叠，Libgdx版本为1.9.14

AndroidGraphics中AndroidApplicationBase改为弱引用

补充原github项目中遗漏的文件

libgdx官方地址：[LibGDX](https://github.com/libgdx/libgdx)

原demo地址(缺少so文件和部分java文件)：[原demo地址](https://github.com/tpnet/Libgdx-Backend-TextureView-Android)

博客地址: [博客地址](https://skyhand.blog.csdn.net/article/details/88540497)  

  
  


原版SurfaceView置于底部效果：

![透明置于底部效果](https://raw.githubusercontent.com/tpnet/LibgdxTextureView/master/pic/SurfaceView%E7%BD%AE%E5%BA%95%E9%83%A8.jpg)





原版SurfaceView透明置于顶部效果：

![置于底部效果](https://raw.githubusercontent.com/tpnet/LibgdxTextureView/master/pic/SurfaceView%E9%80%8F%E6%98%8E%E7%BD%AE%E9%A1%B6.jpg)





修改之后的TextureView与原生View进行透明层叠效果：

![透明层叠效果](https://raw.githubusercontent.com/tpnet/LibgdxTextureView/master/pic/TextureView%E9%80%8F%E6%98%8E%E5%B1%82%E5%8F%A0.jpg)


