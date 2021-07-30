# 说明

imi 框架：https://www.imiphp.com

## 安装

### 方法一

* git 拉取下本项目

* 在本项目目录中，执行命令：`composer update`

### 方法二

Swoole：`vendor/bin/imi-swoole swoole/start`

Workerman：`vendor/bin/imi-workerman workerman/start`

## 启动命令

在本项目目录中，执行命令：`vendor/bin/imi server/start`

## 权限

`.runtime` 目录需要有可写权限

## 测试客户端

`test-client` 目录中附带了测试客户端，可以用于测试。
