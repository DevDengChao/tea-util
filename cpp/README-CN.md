[English](/README.md) | 简体中文


# Darabonba Util SDK Core for C++

![](https://aliyunsdk-pages.alicdn.com/icons/AlibabaCloud.svg)

## 依赖

- [Boost](https://www.boost.org/users/download/) >= 1.58
- [CPPRestSDK](https://github.com/microsoft/cpprestsdk/releases) >= 2.10
- [OpenSSL](https://www.openssl.org/source/) >= 1.0

## 安装

### Linux

```bash
git clone https://github.com/alibabacloud-sdk-cpp/dara-util.git
cd dara-util
sh scripts/install.sh
```

### Windows

1. 使用 git-bash 执行以下命令，从 Github 克隆源码

  ```bash
  git clone https://github.com/alibabacloud-sdk-cpp/dara-util.git
  ```
2. 使用 Visual Studio 进行编译:
  * 安装 [CMake](https://cmake.org/download/) 和 [Visual Studio](https://visualstudio.microsoft.com/zh-hans/)
  * 在项目根目录下创建 `cmake_build` 文件夹
  * 打开 [CMake](https://cmake.org/download/) 软件, 然后进行以下操作
    * 选择 `Browse Source` 为 `源代码目录(darabonba_util)`
    * 选择 `Browse build` 为 `构建目录(cmake_build)`
    * 点击 `configure`
    * 点击 `generate`, 构建 VS 解决方案。

3. 编译安装 C++ SDK
  * 进入 cmake_build 目录，使用 Visual Studio 打开 darabonba_core.sln 解决方案
  * 选择构建 `Release` 输出
  * 并打开配置管理器勾选 `INSTALL`
  * 构建 -> 生成解决方案

## 问题

[提交 Issue](https://github.com/alibabacloud-sdk-cpp/dara-util/issues/new/choose)，不符合指南的问题可能会立即关闭。

## 相关

* [OpenAPI Explorer][open-api]
* [Latest Release][latest-release]
* [Alibabacloud Console System][console]
* [Alibaba Cloud Home Page][aliyun]

## 许可证

[Apache-2.0](/LICENSE.md)

Copyright (c) 2009-present, Alibaba Cloud All rights reserved.

[open-api]: https://api.aliyun.com
[latest-release]: https://github.com/alibabacloud-sdk-cpp/dara-util/releases
[console]: https://home.console.aliyun.com
[aliyun]: https://www.aliyun.com