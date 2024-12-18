# L1G4000 #
## 第一步：创建新的虚拟环境 ##
进入开发机后，创建新的`conda`环境，命名为`llamaindex`，在命令行模式下运行：        
`conda create -n llamaindex python=3.10`           
使用`conda env list`查看本地环境，得到以下输出：              
![image](https://github.com/gaoyukang33/L1G4000/blob/main/IMG/a937d1abb477b884950cf4a917770a3.png)                         
## 第二步：安装必要环境 ##
根据文档内的引导，安装相关包，这部分较简单这里不再赘述        
## 第三步：对比使用RAG前后的模型回答 ##
以下时未使用RAG时的模型回答：          
![image](https://github.com/gaoyukang33/L1G4000/blob/main/IMG/850c0f4ec36631607a22a5d13aed5fa.png)                  
以下是使用RAG后的模型回答：      
![image](https://github.com/gaoyukang33/L1G4000/blob/main/IMG/0fab0f6d874edce1f4d7d0b692d67ba.png)          
## LlamaIndex web ##
根据文档引导，安装必要环境：`pip install streamlit==1.39.0`         
运行`app.py`文件，得到以下输出：              
![image](https://github.com/gaoyukang33/L1G4000/blob/main/IMG/3ab76134be4ea54589d814463bc309d.png)          
不过网站无法打开，其实是因为没有建立好代理，只需要在本地电脑终端中与开发机建立SSH连接，这部分知识我们在第一关已经学过了
![image](https://github.com/gaoyukang33/L1G4000/blob/main/IMG/1a76b585e3747de2a1351b8dbb83166.png)         
后面我们就可以打开网站，我尝试问了几个问题，回答都没有问题：       
![image](https://github.com/gaoyukang33/L1G4000/blob/main/IMG/4e3828a7b273b5e82c0793ce34a1278.png)          
![image](https://github.com/gaoyukang33/L1G4000/blob/main/IMG/682ac35070181ca89446bc69d33724e.png)              
 
