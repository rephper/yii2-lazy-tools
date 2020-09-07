# 说明文档

## 1、通用帮助类
### CacheHelper 缓存
#### redis、文件、片段
### DateTimeHelper 日期、时间
#### 格式化、计算
### ExcelHelper Excel 格式化处理
#### 导出、导出、格式、样式
### FileHelper 文件处理
#### 打包、清空、上传、下载
### NumberHelper 数值 
#### 定义常用数值，处理数据格式、常用计算
### TextHelper 文本处理
#### 字符集、转义、解析、查找、格式化
### WordHelper Word 文件处理
#### 读取、自动填充、导出

## 2、通用基类
### BaseActiveRecord
### BaseActiveQuery
### BaseApiController
### BaseConsoleController
### BaseWebController
### BaseForm
### BaseSearch

## 3、修改过的 migration
### 自动填充 init方法，指定库名、表名
### create文件 自动填充 通用字段定义、表注释、索引
    如：id、status、is_delete、created_at、created_by、updated_at、updated_by、
### add、delete文件 自动填充 $table、$column

## 4、修改过的 gii
### ActiveRecord 继承新的基类
### ActiveQuery  继承新的基类
### ApiController  继承新的基类