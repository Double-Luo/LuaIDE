LuaIDE
======
Author:罗建辉
CreateTime:2017-05-26
目的：强化自身数据展示的能力
=============环境的安装==============
1、node.js的下载和安装：
	下载地址：http://download.csdn.net/download/u010989191/9493005
	2、Electron教程：
		教程地址：http://www.cnblogs.com/chris-d-nerd/p/5648317.html
		3、Git教程
			教程地址：http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/00137396287703354d8c6c01c904c7d9ff056ae23da865a000

			============官网例子的演示==========
			1、https://electron.atom.io/docs/tutorial/quick-start/
				核心：--index.html	--初始
						--main.js	--主线程
								--package.json  --包

								============Git仓库创建==========
								1、git init	初始化
								2、git add	放到暂存区（Stage)
								3、git commit -m ""  	提交到仓库Master（与add有先后顺序）
								4、git status	获取仓库状态
								5、git diff	仓库修改详细
								6、git log --pretty=oneline	仓库log
								7、git reset --hard commit_id	仓库回退，HEAD当前版本，^上一个版本，~100前100个版本
								8、git reflog	仓库回退log
								9、git checkout -- file		文件撤销修改（版本库的文件替换工作区的版本）
								10、git reset HEAD file		文件暂存区撤销
								11、git rm			删除库文件
								12、ssh-keygen -t rsa -C "youremail@example.com"创建SSHKey，并在githube上添加key
								13、git remote add origin git@github.com:Double-Luo/GitPage.git		添加远程库
								14、git push -u origin master	推送本地库到远程库
								15、git clone	克隆远程库

								============VSCode安装==========
								1、官网地址：https://code.visualstudio.com/
								2、VSCode启动Electron：
								3、VSCODE的使用：http://www.cnblogs.com/lianmin/p/5499266.html
								4、VSCODE调试 ： electron . --debug-brk=5858，然后
								5、VS调整字体：http://jingyan.baidu.com/album/72ee561a622964e16138dffa.html?picindex=5


								============Electron中文文档======
								https://github.com/electron/electron/tree/master/docs-translations/zh-CN

								==============CodeMirror==========


