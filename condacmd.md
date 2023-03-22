# 更推荐使用miniconda
## 创建python虚拟环境
``` conda create -n <your-environment-name> python==<python-version> ```

## 创建完成后即可激活并进入虚拟环境
``` conda activate <your-environment-name>```

## 查看已创建的python虚拟环境
``` conda info --envs ```

## 删除虚拟环境以及所有的packages
``` conda remove -n <your-environment-name> --all```
### 若只删除一个package
``` conda remove <package-name>```

**个人建议可以使用2种方式管理**
    1. 使用项目名称为虚拟环境名称
    2. 使用主要的框架名称作为虚拟环境名称
