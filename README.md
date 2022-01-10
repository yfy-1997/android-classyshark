# ClassyShark

### 介绍

![alt text](https://github.com/borisf/classyshark-user-guide/blob/master/images/5%20ClassesDexData.png)

ClassyShark 是一个针对 Android 开发人员的独立二进制检查工具。它可以可靠地浏览任何 Android 可执行文件，并显示重要信息，如类接口和成员，dex 计数和依赖性。ClassyShark 支持多种格式，包括库(。德克斯。你知道吗。可执行文件。Apk.罚钱。类)和所有 Android 二进制 xml: AndroidManifest、资源、布局等。

### 相关连接
* [User guide](https://github.com/borisf/classyshark-user-guide)
* [Command-line reference](https://github.com/google/android-classyshark/blob/master/CommandLine.pdf)
* Gradle [sample](https://github.com/google/android-classyshark/tree/master/Samples/SampleGradle)
* [Vision and Strategy](https://docs.google.com/document/d/1sK_WNzHn_6Q1V_dohxrtk1tlsPXsi9cEVnIuYuVig0M/edit?usp=sharing)

### 下载
To run, grab the [latest JAR](https://github.com/google/android-classyshark/releases)
and run `java -jar ClassyShark.jar`.

### 以文本格式导出数据
* [Exporter](https://medium.com/@BorisFarber/exporting-data-from-classyshark-e3cf3fe3fab8#.deec4nyjq)
* API finder :construction: work in progress

### Develop
1. Clone the repo
2. Open in your favorite IDE/editor
3. Build options:
     * IntelliJ - builds automatically when exporting the project 
     * [Gradle script](https://github.com/google/android-classyshark/blob/master/ClassySharkWS/build.gradle)
     * [RetroBuild](https://github.com/borisf/RetroBuild)

### Arch Linux

If you're running Arch Linux you can install the latest [prebuilt jar from the AUR](https://aur.archlinux.org/packages/classyshark/).

### 依赖
* [dexlib2](https://github.com/JesusFreke/smali/tree/master/dexlib2) by jesusfreke
* [guava](https://github.com/google/guava) by Google
* [ASM](http://asm.ow2.org/) by OW2
* [ASMDEX](http://asm.ow2.org/asmdex-index.html) by OW2
* [java-binutils](https://github.com/jawi/java-binutils) by jawi
* [BCEL](https://commons.apache.org/proper/commons-bcel) by Apache

### Support
If you've found an error, please file an issue:

https://github.com/google/android-classyshark/issues

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub.

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



