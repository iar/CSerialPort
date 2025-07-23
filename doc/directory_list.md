update : 2025-07-23

```
CSerialPort # root
+--- .clang-format # code format 代码规范
├── bindings # 第三方语言接口
│   ├── c # c interface c接口
│   ├── csharp # csharp interface c#接口
│   ├── java # java interface java接口
│   ├── javascript # javascript interface javascript接口
│   ├── nodejs # nodejs interface nodejs接口
│   └── python # python interface python接口
│   └── rust # rust interface rust接口
├── CHANGELOG.md # change log 修改日志
├── cmake # cross compile 交叉编译
├── CMakeLists.txt
├── doc # document 文档
├── examples # example 示例程序
│   ├── CommAndroid # CSerialPort Android Demo Android程序示例
│   ├── CommElectron # CSerialPort Electron Demo Electron程序示例
│   ├── CommMFC # CSerialPort MFC Demo MFC程序示例
│   ├── CommNoGui # CSerialPort No Gui Demo 无界面程序示例
│   ├── CommNoGuiProtocol # CSerialPort common communication protocol parser Demo 通用通信协议解析示例
│   ├── CommQT # CSerialPort QT Demo QT程序示例
│   ├── CommTui # CSerialPort tui Demo 文本界面程序示例
│   ├── CommWeb # CSerialPort Web Demo Web程序示例
│   ├── CommWebview # CSerialPort Webview Demo Webview程序示例
│   ├── CommWXWidgets # CSerialPort wxwidgets Demo wxwidgets界面程序示例
├── include # headers 头文件
│   └── CSerialPort
│       ├── ibuffer.hpp # lightweight cross-platform buffer library 轻量级跨平台缓冲区类
│       ├── ilog.hpp # lightweight cross-platform log library 轻量级跨平台日志类
│       ├── ithread.hpp # lightweight cross-platform thread library 轻量级跨平台线程类
│       ├── itimer.hpp # lightweight cross-platform timer library 轻量级跨平台定时器类
│       ├── iutils.hpp # lightweight cross-platform utils library 轻量级跨平台工具类
│       ├── IProtocolParser.h # common comunication protocol implement 通用通信协议接口类
│       ├── SerialPortBase.h # CSerialPort Base class 串口基类
│       ├── SerialPort_global.h # Global difine of CSerialPort 串口全局定义 
│       ├── SerialPort_version.h # CSerialPort version 版本定义
│       ├── SerialPort.h # lightweight cross-platform serial port library 轻量级跨平台串口类库
│       ├── SerialPortHotPlug.h # CSerialPort Hot Plug class 串口热插拔类
│       ├── SerialPortHotPlug_win.h # CSerialPort Hot Plug class for windows windows串口热插拔类
│       ├── SerialPortHotPlug_linux.h # CSerialPort Hot Plug class for linux linux串口热插拔类
│       ├── SerialPortHotPlug_mac.h # CSerialPort Hot Plug class for mac mac串口热插拔类
│       ├── SerialPortInfoBase.h # CSerialPortInfo Base class 串口信息辅助类基类
│       ├── SerialPortInfo.h # CSerialPortInfo class 串口信息辅助类
│       ├── SerialPortInfoUnixBase.h # CSerialPortInfo unix class unix串口信息辅助类基类
│       ├── SerialPortInfoWinBase.h # CSerialPortInfo windows class windows串口信息辅助类基类
│       ├── SerialPortListener.h # CSerialPortListener interface class 串口事件监听接口类
│       ├── SerialPortUnixBase.h # CSerialPort unix Base class unix串口基类
│       └── SerialPortWinBase.h # CSerialPort Windows Base class windows串口基类
├── lib # lib 库目录
├── LICENSE # LGPLv3 with LGPL-3.0-linking-exception license
├── pic # picture 图片
├── README.md
├── README_zh_CN.md
├── src # source 源代码
├── test # unit test 单元测试
└── VERSION # version 版本号
```
