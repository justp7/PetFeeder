# 宠物喂食器
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.
For more information, please check Tuya Developer Website.
1. 放粮控制
   1. WIFI控制放粮
   2. 定时放粮
   3. 定量控制
   4. 粮量检测
2. 环境监测
3. 双电源供电
4. 拓展功能
   1. 出粮计划设置
   2. 按键出粮/红外遥控出粮
   3. 语音识别放粮

## 主要功能

### 放粮控制

#### WIFI控制放粮

通过WIFI模组WB3S与涂鸦智能APP建立联系，执行相关放粮操作。

#### 定时放粮

通过涂鸦APP设置定时时间，到达时间后进行操作下发，执行放粮操作。

#### 定量控制

通过控制电机转动步数控制宠物食物放粮数量。

#### 粮量检测

通过超声波模块检测宠物食物的位置即可获得粮食的剩余容量，用于及时提醒铲屎官进行粮食补充。

### 环境监测

通过SHT30进行监测宠物环境，方便进行设备联动操作。

### 双电源供电系统

1. 支持外接5V（USB）进行供电.
2. 内置充电电路与切换电路，当外部停电时自动切换到锂电池供电。

### 拓展功能

#### 出粮计划设置

最多可设置5种时间段的出粮操作。

#### 按键出粮/红外遥控出粮

可通过机械按键/红外遥控器控制系统执行放粮操作。

#### 语音识别放粮（依据涂鸦提供开发板）

## 硬件组成

### 涂鸦WIFI三明治开发板

### 涂鸦H桥电机驱动板

### 涂鸦18650电池供电板

### Arduino开发板