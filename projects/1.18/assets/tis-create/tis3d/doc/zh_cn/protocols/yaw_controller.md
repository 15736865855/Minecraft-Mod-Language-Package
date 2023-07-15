# 方向机
![方向机受损！](block:createbigcannons:yaw_controller)

串口模块可以与方向机交互，回报其附着火炮的方向角。读取操作会以整数形式返回火炮的方向角，**单位为 十分之一度**，范围为[0,3600]。此协议不支持写入操作 。试图读取没有附着火炮的方向机是未定义行为。