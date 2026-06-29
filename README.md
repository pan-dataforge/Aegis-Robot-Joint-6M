# Aegis Robot Joint Controller

> 从 0 到 1构建的机器人嵌入式关节控制与诊断项目。

## Project Goal
半年内完成 STM32、FreeRTOS、电机控制、CAN、Linux C++、ROS 2 和最小 TinyML 闭环，用真实代码、硬件、测试和 Git 记录证明嵌入式工程能力。

## Current Status
- Current stage: M0
- Current week: Not started
- Current version: v0.0.0

## Development Rule
所有正式功能都通过：Issue → Branch → Code → Test → Commit → Push → PR → Review → Merge。

## Safety
AI、ROS 2、Linux 和上位机不能绕过 MCU 安全状态机直接驱动电机；物理急停必须切断电机功率。