# internLM_Training
# （一）关卡任务清单

|            | 任务描述                                      | 完成所需时间 |
| ---------- | --------------------------------------------- | ------------ |
| 闯关任务   | 完成SSH连接与端口映射并运行`hello_world.py`   | 10min        |
| 可选任务 1 | 将Linux基础命令在开发机上完成一遍             | 10min        |
| 可选任务 2 | 使用 VSCODE 远程连接开发机并创建一个conda环境 | 10min        |
| 可选任务 3 | 创建并运行`test.sh`文件                       | 10min        |

# （二）完成记录
## 1、闯关任务
### 配置SSH公钥进行SSH远程连接

（1）本地终端：使用 ssh-keygen 命令生成密钥。

![image](https://github.com/user-attachments/assets/6dc4e09d-db6b-4572-b031-a24f2f897982)

（2）本地终端：使用cat id_rsa.pub命令查看公钥内容，并将长字符串进行复制。

![image](https://github.com/user-attachments/assets/0edea011-2975-4564-b29c-38cc5eada922)

（3）打开开发机，点击“添加公钥”进入SSH对话框。

![image](https://github.com/user-attachments/assets/3b8b4828-99f6-4779-a194-19a89f1f8269)

（4）将上一步复制的字符串黏贴并创建公钥。

![image](https://github.com/user-attachments/assets/1c45ad52-17e5-400c-92fc-e7b54d33da51)

（5）复制SSH对话框中的“登录命令”粘贴到本地终端中，回车，即可登录，无需输入密码。

![image](https://github.com/user-attachments/assets/60b02aa1-e421-4029-affd-c633c22a37c3)

（6）安装fradio

![Snipaste_2024-09-18_17-24-32](https://github.com/user-attachments/assets/7b50cdb7-e98e-4cc3-85e0-f4c5236d06d5)

（7）在开发机的Juperter lab中，创建helloworld.py并运行该文件。

![Snipaste_2024-09-18_17-30-10](https://github.com/user-attachments/assets/274b6d27-9d7a-4922-ba34-a83c9f41136b)

（8）通过本地浏览器，验证端口映射是否成功。
![image](https://github.com/user-attachments/assets/0d0eb489-73d7-43fc-8b39-ab6a6952b9ca)

## 2、可选任务 1
通过进入开发机，使用juperter lab输出Hello World~

![image](https://github.com/user-attachments/assets/ad11c846-4984-49f7-ae51-bce601e97739)

## 3、可选任务 2
使用VScodeIDE进行SSH远程连接：

（1）安装Remote-SSH

![image](https://github.com/user-attachments/assets/c8ac6b88-9256-41b5-92eb-3794659841a0)

（2）将SSH对话框中的“登录命令”复制到如图所示

![image](https://github.com/user-attachments/assets/94242545-f0ab-4b4d-872b-e26af1d8eaea)



