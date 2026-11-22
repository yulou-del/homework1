作业1 led
PA1连接LED，并命名，后续PA1全部用LED来写
通过HAL_Delay等250ms，控制灯的亮灭

作业2 LED_NoDelay
通过TIM2定时器中断控制
在 TIM2 输入时钟为72MHz的配置下，预分频值为7199，自动重装载值为2499，每250ms产生一次更新中断。

作业3 LED_EXITcontrol
使用PA0连接按键，采用内部上拉，按键按下后连接到GND
按键触发中断后，延时20ms，翻转 LED 状态。