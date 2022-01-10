# ClassyShark

### 介绍

![alt text](https://github.com/borisf/classyshark-user-guide/blob/master/images/5%20ClassesDexData.png)

ClassyShark 是一个针对 Android 开发人员的独立二进制检查工具。它可以可靠地浏览任何 Android 可执行文件，并显示重要信息，如类接口和成员，dex 计数和依赖性。ClassyShark 支持多种格式，包括库(。德克斯。你知道吗。可执行文件。Apk.罚钱。类)和所有 Android 二进制 xml: AndroidManifest、资源、布局等。

### 相关连接
* [用户向导](https://github.com/borisf/classyshark-user-guide)
* [命令行引用](https://github.com/google/android-classyshark/blob/master/CommandLine.pdf)
* Gradle [例子](https://github.com/google/android-classyshark/tree/master/Samples/SampleGradle)
* [Vision and Strategy](https://docs.google.com/document/d/1sK_WNzHn_6Q1V_dohxrtk1tlsPXsi9cEVnIuYuVig0M/edit?usp=sharing)

### 下载
使用方法, 下载 [最新版](https://github.com/google/android-classyshark/releases)
运行 `java -jar ClassyShark.jar`.

### 以文本格式导出数据
* [导出](https://medium.com/@BorisFarber/exporting-data-from-classyshark-e3cf3fe3fab8#.deec4nyjq)
* API finder: 构建: 正在进行的工作

### Develop
1. 克隆
2. 在您最喜欢的 IDE/编辑器中打开
3. 构建选项:
     * IntelliJ - 在导出项目时自动构建
     * [Gradle 脚本](https://github.com/google/android-classyshark/blob/master/ClassySharkWS/build.gradle)
     * [RetroBuild](https://github.com/borisf/RetroBuild)

### Arch Linux

如果你正在运行 Arch Linux，你可以安装最新的 [prebuilt jar from the AUR](https://aur.archlinux.org/packages/classyshark/).

### 依赖
* [dexlib2](https://github.com/JesusFreke/smali/tree/master/dexlib2) by jesusfreke
* [guava](https://github.com/google/guava) by Google
* [ASM](http://asm.ow2.org/) by OW2
* [ASMDEX](http://asm.ow2.org/asmdex-index.html) by OW2
* [java-binutils](https://github.com/jawi/java-binutils) by jawi
* [BCEL](https://commons.apache.org/proper/commons-bcel) by Apache

### 支持
如果你发现了一个错误，请提交问题到:

https://github.com/google/android-classyshark/issues

补丁是鼓励的，并且可以通过分叉这个项目和
通过GitHub提交一个pull request

License
=======

    Copyright 2020 Google, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.



