### virtualenvwrapper

1. 安装
```
pip install virtualenvwrapper
```

2. 用法
  - 创建虚拟环境
  ```
  mkvirtualenv envname
  ```
  - 创建指定解释器的虚拟环境
  ```
  mkvirtualenv -p python3 envname
  ```
  - 启动虚拟环境
  ```
  workon envname
  ```
  - 退出虚拟环境
  ```
  deactivate
  ```
  - 删除虚拟环境
  ```
  rmvirtualenv envname
  ```
