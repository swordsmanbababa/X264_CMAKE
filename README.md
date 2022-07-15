# X264_CMAKE
使用visual studio编译运行X264

## Environment
- windows 10
- visual studio 2019
- vscode + cmake扩展

## Quick Start

### 1 使用cmake生成VS工程
  建议直接使用vscode中的CMAKE插件。
  ![image height = "300" width="800"](https://user-images.githubusercontent.com/27400085/179201068-46ddf6d2-ffd9-4b5e-b7a4-cf44a80deced.png)
  - 使用vscode打开工程
  - step1 选择cmake选项
  - step2 点击配置所有项目
  <img src="https://user-images.githubusercontent.com/27400085/179201705-a4501e8b-6334-4adc-9bcc-a3f5d117442c.png" height = "500" width="1050">
### 2 从build目录选择生成的  x264.sln  文件打开
  <img src="https://user-images.githubusercontent.com/27400085/179202071-4b0c7553-f306-4442-9f19-eb0e0c4d8101.png" height = "500" width="1050">
  
### 3 配置运行参数

  - 解决方案资源管理器-> x264 -> 属性： 设置为启动项
  - 解决方案资源管理器-> x264 -> 属性：打开属性面板，配置命令参数（-o result bus_cif_352x288.yuv）
   <img src="https://user-images.githubusercontent.com/27400085/179202732-611fd9d7-60fa-4148-b085-a7ad0790d2d4.png" height = "300" width="1050">
