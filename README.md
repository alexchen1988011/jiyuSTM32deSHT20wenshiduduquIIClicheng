# 基于STM32的SHT20温湿度读取IIC例程

本仓库提供了一个基于STM32F103ZET6微控制器的SHT20/30温湿度传感器读取例程。该例程通过IIC通信方式实现温湿度数据的读取，并提供了简单的数据显示功能。代码经过测试，可以直接使用。此外，仓库中还附带了实物连接图，方便用户进行硬件连接。

## 功能特点

- **硬件平台**：STM32F103ZET6
- **传感器**：SHT20/30
- **通信方式**：IIC
- **功能**：读取温湿度数据并显示
- 8*附带内容**：实物连接图

## 使用说明

1. **硬件连接**：
   - 根据附带的实物连接图，将SHT20/30传感器正确连接到STM32F103ZET6开发板上。
      - 确保电源和地线连接正确，避免短路。

      2. **软件配置**：
         - 将仓库中的代码导入到你的STM32开发环境中（如Keil、STM32CubeIDE等）。
            - 根据实际情况配置IIC通信引脚。

            3. **编译与下载**：
               - 编译代码并将其下载到STM32F103ZET6开发板上。
                  - 启动开发板，观察温湿度数据的读取与显示情况。

                  ## 注意事项

                  - 请确保硬件连接正确，避免因连接错误导致的设备损坏。
                  - 代码中已包含基本的错误处理机制，但建议在使用过程中进行进一步的测试和优化。

                  ## 贡献

                  欢迎大家提出改进建议或提交代码优化，共同完善本例程。

                  ## 许可证

                  本项目采用MIT许可证，详情请参阅LICENSE文件。

                  ## 下载链接
                  [基于STM32的SHT20温湿度读取IIC例程](https://pan.quark.cn/s/29f6834b500c)

                  ## 说明

                  该仓库仅用于学习交流，请勿用于商业用途。
