# Installing-Instruction-for-Autokeras
# Autokeras安装指南

- Installing Instruction for Python Autokeras 0.3.5

###############################
###############################

第1步：安装Anaconda

从 https://www.anaconda.com/download/ 下载最新的Anaconda 64位版本，且安装过程中,适用用户选择Just Me，且“Add Anaconda to my PATH environment variable”选择勾上

第2步：创建虚拟环境(Python3.6)

在Windows的CMD里输入conda create -n autok python=3.6

第3步：安装Spyder

在Anaconda Navigator里的Environments里的autok，选择安装spyder

第4步：安装.NET Framework 4.7.2或更高版本

从 https://dotnet.microsoft.com/download/dotnet-framework-runtime/net472 下载并安装.NET Framework 4.7.2

第5步：安装Visual C++ 15

从 https://visualstudio.microsoft.com/zh-hans/thank-you-downloading-visual-studio/?sku=BuildTools&rel=15&rr=https%3A%2F%2Fwww.scivision.co%2Fpython-windows-visual-c%2B%2B-14-required%2F
下载Microsoft Visual C++ Redistributable for Visual Studio 2017，安装时选择安装"Visual C++生成工具"(但其右侧可选的子项全部选择不安装)

第6步：安装AutoKeras 0.3.5

(6.1) 在Windows的CMD里输入conda activate autok

(6.2) 在Windows的CMD(autok)里输入pip install tensorflow

(6.3) 在Windows的CMD(autok)里输入pip install keras

(6.4) 在Windows的CMD(autok)里输入pip install http://download.pytorch.org/whl/cu80/torch-0.4.1-cp36-cp36m-win_amd64.whl

(6.5) 在Windows的CMD(autok)里输入pip install autokeras=0.3.5



#################################
##English version
#################################

Step 1：Install Anaconda

Download Anaconda 64bit from https://www.anaconda.com/download/ , during installing, choose "Just Me" and “Add Anaconda to my PATH environment variable”.

Step 2: Create a virtual environment for Python3.6

At Windows CMD, type "conda create -n autok python=3.6"

Step 3: Install Spyder for the virtual environment above

Install Spyder at Anaconda Navigator with Environments selecting "autok"

Step 4: Install .NET Framework 4.7.2 or above

Download https://dotnet.microsoft.com/download/dotnet-framework-runtime/net472 and install.NET Framework 4.7.2

Step 5: Install Visual C++ 15

Download https://visualstudio.microsoft.com/zh-hans/thank-you-downloading-visual-studio/?sku=BuildTools&rel=15&rr=https%3A%2F%2Fwww.scivision.co%2Fpython-windows-visual-c%2B%2B-14-required%2F
 and Install Microsoft Visual C++ Redistributable for Visual Studio 2017. During installing, select the "Visual C++ tools", but not selecting the sub-installtion.

Step 6: Install AutoKeras 0.3.5

(6.1) At Windows CMD, type "conda activate autok"

(6.2) At Windows CMD(autok), type "pip install tensorflow"

(6.3) At Windows CMD(autok), type "pip install keras"

(6.4) At Windows CMD(autok), type "pip install http://download.pytorch.org/whl/cu80/torch-0.4.1-cp36-cp36m-win_amd64.whl"

(6.5) At Windows CMD(autok), type "pip install autokeras=0.3.5"
