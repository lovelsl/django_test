# django_test 说明：


这是一个 GIT 测试项目，请不要直接在 main 分支操作。

本 GIT 项目用于测试所有人对 GIT 工具的熟悉度，请所有人按照以下要求创建分支。


## 分支创建规则

分支命名语法格式：
    dev/test/your_name-for-git

如lsl的分支：
    dev/test/leisonglin-for-git


## commit 提交规则

commit 语法格式：
   <type>(scope): <subject>

type 值:
feat: 实现了一个功能
fix:  修复了某一个bug
docs: 说明文档累内容
test： 测试类内容


scope 值:
	该内容一般为项目分解的模块，当前统一写为 django

subject 值:
	该内容为对应 type 下执行的操作 	

示例：
     git commit -m "feat(django): 初始化项目"
	
	

