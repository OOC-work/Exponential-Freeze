# Exponential-Freeze-
指數性降溫的炒冰機Exponential cooling ice fryer

# 項目介紹 
有優秀的控制單元和計算單元，來進行運算的一台炒冰機，以卻本溫度變化小，且有多功能控制。  
![image](https://github.com/OOC-work/Exponential-Freeze-/blob/main/320790861_5880913735262653_5458695470784118876_n.jpg)  
![image](https://github.com/OOC-work/Exponential-Freeze-/blob/main/320804428_5912045948846169_7763212857853034712_n.jpg)  
# 項目內容
由硬體+軟體構成，主要以硬體輔軟體，軟體只是用來收發訊號和運算，硬體支撐大部分項目，以超規格來達到良好的結果。  
第一版:Nextion的TTF檔+Arduino的Arduino.ino  
第二版:主要是Arduino的Arduino.ino
# 項目核心
## 核心運算:
第一版:PID算法(Proportional Integral Derivative)   
第二版:未來:MPC(Model Predictive Controller)+PID(Proportional Integral Derivative)  
## 核心配置:
第一版:使用ATmega2560來控制多個多元，但沒網路功能。  
第二版:使用ESP-32-32UE體積小且有藍牙和Wi-Fi功能，但擴充性低。 
## 核心控制單元:
第一版:使用現成模塊AOD4184A可控制電壓26V電流15A，400W的電路。  
第二版:使用EL817(C)光電偶隔離大電、小電，Mosfet更改為SQJA66EP-T1_GE3控制電壓60V電壓75A，整整4500W的控制能力。  
## 核心程式:
# 項目畫廊





















