# 桌面串流


![](https://img.shields.io/badge/LICENSE-MIT-green.svg)  ![](https://img.shields.io/badge/CODE-Kotlin-green.svg)  ![](https://img.shields.io/badge/BUILD-Gradle-green.svg)  ![](https://img.shields.io/badge/TYPE-Application-green.svg)  

一个轻量级桌面转发软件，使用Kotlin开发

## 构建运行

#### 构建要求：

1. Oracle JDK 8 或者 OpenJDK 8 +  OpenJFX 8
2. 磁盘剩余空间 512M 以上 

### Windows

```cmd
git clone https://github.com/ExplodingFKL/JRemoteDesktop
cd JRemoteDesktop
gradlew.bat build
gradlew.bat bootRun
```

### MacOS / Linux
```bash
git clone https://github.com/ExplodingFKL/JRemoteDesktop
cd JRemoteDesktop
./gradlew build
./gradlew bootRun
```

## LICENSE

```
Copyright (c) 2013, Aldo Cortesi. All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```