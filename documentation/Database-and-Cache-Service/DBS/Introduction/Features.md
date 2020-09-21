# 产品功能

## 数据库备份

支持将自建数据库的数据备份到云端，目前支持源库通过公网连接到数据库备份 DBS进行数据备份。

## 备份方式

支持逻辑备份，并可以按需开启增量备份；目前仅支持对源库进行整库备份。

## 数据库恢复

支持使用数据库备份 DBS中保存的备份文件，将数据恢复到自建数据库，目前支持数据库备份 DBS通过公网连接到目标库进行数据恢复。

## 备份文件下载

提供备份文件下载功能，支持将备份文件保存到本地；目前全量备份文件和增量备份备份都提供了下载链接，您可以将指定的备份文件下载到本地。

## 数据库类型

目前支持的数据库引擎和版本如下：
- MySQL ：5.6、5.6、5.7
- Percona：5.7
