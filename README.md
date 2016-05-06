# OgreDependencies
Ogre 3D Cross-Platform Dependencies Libraries

> ogredeps-src is fork from https://bitbucket.org/cabalistic/ogredeps/overview

- 问了和Ogre库编译同版本库，执行cmake时需输入以下命令：
> cmake -D OGRE_BUILD_PLATFORM_APPLE_IOS=1 OGRE_CONFIG_ENABLE_LIBCPP_SUPPORT=1 -G Xcode ..
确保以下编译器选择正确：
- C Language Dialect : Compiler Default
- C++ Language Dialect : c++11
- C++ Standard Library : libc++(LLVM C++ standard library with C++11 support)
