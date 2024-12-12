# CUDA-PyTorch
## 安装CUDA
跟着这个视频尝试安装CUDA：https://www.bilibili.com/video/BV1eh4y1Y7kT  
CUDA安装地址：https://pytorch.org/get-started/locally/  
右键【win】打开终端，输入nvidia-smi，在CUDA Version中查看显卡支持的CUDA版本  
https://developer.nvidia.com/cuda-12-4-0-download-archive找到对应版本下载链接（这个是12.4.0）  
https://developer.nvidia.com/rdp/cudnn-archive找到对应版本的cuDNN下载压缩包（12.x）  
## 安装pytorch
进入官网：https://pytorch.org/  
选择对应的pytorch版本，例如12.4  
![image](https://github.com/user-attachments/assets/1d79986c-ef1f-4239-ac20-13a65f87ed97)  
复制最后一行“Run this Command:”，其中python版本的CUDA12.4适配的pytorch为：`<pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124>`  
将上面这行pip的命令，粘贴到jupyter对话框中或者python命令行中并执行，等待安装成功（如果在内地第一次安装wheel可能稍微久一点，耐心等待，报错了就百度一下，实在不行问我）  
