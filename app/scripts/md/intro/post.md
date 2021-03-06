# **四軸飛高高海報專區**

## 內容

指導老師:黃敬群

組員:黃大峯、劉政德、楊承翰、鄭聖文

摘要：本專題以[STM32F405R](http://www.st.com/web/catalog/mmc/FM141/SC1169/SS1577/LN1035/PF252144)G(ARM Cortex M4)為基礎嵌入式系統架構，在Linux環境下開發四軸飛行器，移植FreeRTOS作業系統到飛控板，並經由飛控板進行控制，過程中透過PWM輸入訊號控制四顆無刷直流馬達(BLDC)，藉由三軸陀螺儀與三軸加速規計算其姿態角，再經由PID控制器來控制其姿態達成穩定的飛行模式。

功能：

· Support commercial R/C remoter(Futaba)

· Support linenoise text editing environment with a Shell

· Shell commands 

· QuadCopter status monitor

· Online tuning PID parameter

· Save information in SD Card

圖片文字大約位置擺放：

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.88862_1388810374493_ok.png)

 P.S.目前缺四軸實體圖看還需要什麼圖這邊貼給我,word集中我這邊修改

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.88862_1388753275463_DSCF4390.JPG)

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.88862_1388810408799_DSCF4391.JPG)

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.94311_1388655126576_QCopterFC_System.png)

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.88862_1388744696513_hackpad.com_Y38T9JXygI8_p.88862_1388674362841_System_Structure.bmp.png)

![](/static/img/misc/status-ball.gif)

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.88549_1388756487153_WEB_GUI .png)

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.88549_1388756494972_acc_plot.png)![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.88549_1388756494991_angular_rate_plot.png) 

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_NcfzuQiG05v_p.88862_1388843099366_123.bmp)