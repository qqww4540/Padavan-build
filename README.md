# Padavan-build说明

步骤

0.点击右上角的Fork按钮，进入自己fork后的仓库。

1.修改/workflows/build-padavan.yml里的插件与机型。修改TNAME: K2P 中的K2P为需要编译的型号，注意名称要与trunk/configs/templates/目录下的名字
相同。

  修改后commit changes保存。

2.点击页面上部的Actions按钮，点击I understand my workflows，go ahead and enable them绿色按钮启用action，然后Run workflow

编译完成后在Actions页面底部下载固件。
