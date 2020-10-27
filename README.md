<p align="center">
  <img src="https://raw.githubusercontent.com/filebrowser/logo/master/banner.png" width="550"/>
</p>

⚠️ WARN: **This project will not be developed anymore. If you're willing to take over this project, please read [#532](https://github.com/filebrowser/filebrowser/issues/532) for more info!**

![Preview](https://user-images.githubusercontent.com/5447088/50716739-ebd26700-107a-11e9-9817-14230c53efd2.gif)

[![Travis](https://img.shields.io/travis/com/filebrowser/filebrowser.svg?style=flat-square)](https://travis-ci.com/filebrowser/filebrowser)
[![Go Report Card](https://goreportcard.com/badge/github.com/filebrowser/filebrowser?style=flat-square)](https://goreportcard.com/report/github.com/filebrowser/filebrowser)
[![Documentation](https://img.shields.io/badge/godoc-reference-blue.svg?style=flat-square)](http://godoc.org/github.com/filebrowser/filebrowser)
[![Version](https://img.shields.io/github/release/filebrowser/filebrowser.svg?style=flat-square)](https://github.com/filebrowser/filebrowser/releases/latest)
[![Chat IRC](https://img.shields.io/badge/freenode-%23filebrowser-blue.svg?style=flat-square)](http://webchat.freenode.net/?channels=%23filebrowser)

filebrowser provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory. It can be used as a standalone app or as a middleware.

## Features

Please refer to our docs at [filebrowser.xyz/features](https://filebrowser.xyz/features)

## Install

Please refer to our docs at [filebrowser.xyz](https://filebrowser.xyz/).

## Usage

Please refer to our docs at [filebrowser.xyz/usage](https://filebrowser.xyz/usage).

## Contributing

Please refer to our docs at [filebrowser.xyz/contributing](https://filebrowser.xyz/contributing).

CMD 命令:

E

filebrowser.exe

#创建并初始化数据库
filebrowser -d E:/NasManager/filebrowser.db config init

#设置filebrowser监听地址
filebrowser -d E:/NasManager/filebrowser.db config set --address 0.0.0.0

#设置filebrowser监听端口
filebrowser -d E:/NasManager/filebrowser.db config set --port 8099

#设置filebrowser语言环境
filebrowser -d E:/NasManager/filebrowser.db config set --locale zh-cn

#设置filebrowser日志文件位置
filebrowser -d E:/NasManager/filebrowser.db config set --log /data/filebrowser/logs/filebrowser.log

#设置filebrowser Web控制台界面账号和密码
filebrowser -d E:/NasManager/filebrowser.db users add root 123456 --perm.admin

#启动filebrowser
filebrowser -d E:/NasManager/filebrowser.db

