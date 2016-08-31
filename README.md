# 终端命令

> 基本命令
* 显示当前目录的路径
  ```
  pwd
  ```

* 显示当前目录的内容
  ```
  ls params dirname
     params  -w 显示中文，
          -l 详细信息，
          -a 包括隐藏文件
  ```
* 转换目录
  ```
  cd dirname
  cd . ：当前目录
  cd .. ：返回上一级目录
  cd ../.. ：返回上两级目录
  cd ../.. /..：返回上三级目录
  ```
* 建立新目录
  ````
  mkdir dirname
  ````
* 删除目录
  ```
  rmdir dirname
  ```
* 移动目录
  ```
  mvdir dir1 dir2
  ```
* 比较两个目录的内容
  ```
  dircmp dir1 dir2
  ```
* 新建文件
  ```
  touch filename
  ```
* 拷贝文件
  ```
   cp 参数 源文件 目标文件
  ```
* 删除文件
  ```
  rm 参数 文件
      参数－rf 表示递归和强制，千万要小心使用，如果执行了 rm -rf / 你的系统就全没了
  ```
* 移动文件
  ```
   mv 源文件 目标文件
  ```
* 文本编辑
  ```
  nano filename
  ```
* 清屏
  ```
  clear
  ```