### discription
本实验要求设计一个十字路口的交通灯系统。<br>
系统输入：时钟CLK、复位CLR、交通灯正常启动start、主干道阻塞不通行stopa，次干道阻塞不通行stopb。系统暂停pause按钮用于暂停系统，便于观察实验结果。<br>
系统输出：在数码管（高2片）上显示主干道读秒倒计时，在数码管（低2片）上显示次干道读秒倒计时，6个LED灯分别显示主干道和次干道的红绿黄灯。<br>
系统的运行规则是：<br>
（1）按下复位按钮，主干道和次干道的红灯皆亮，且主干道和次干道都不显示读秒，4个数码管显示“----”；<br>
（2）当主干道阻塞时，主干道和次干道都不显示读秒，数码管无显示，主干道的红灯亮，次干道绿灯长亮；<br>
（3）当次干道阻塞时，主干道和次干道都不显示读秒，数码管无显示，次干道的红灯亮，主干道绿灯长亮；<br>
（4）当按下启动按钮，系统启动；<br>
（5）交通灯正常工作时，主干道和次干道都显示读秒，系统在四个状态之间切换，这4个状态分别是：state1：主干道通行次干道禁行，主干道绿灯亮，次干道红灯亮，时长35秒；state2：主干道黄灯亮，次干道红灯亮，时长5秒；state3：次干道通行，主干道禁行，主干道红灯亮，次干道绿灯亮，时长25秒；state4：主干道红灯亮，次干道黄灯亮，时长5秒。状态转换表如表1所示。<br>
（6）当暂停按钮按下时，主干道和次干道计数暂停，红黄绿灯保持不变，观察结果。松开暂停按钮，系统继续运行<br>
状态	主干道	次干道	时间（秒）<br>
State1	绿灯亮	红灯亮	35<br>
State2	黄灯亮	红灯亮	5<br>
State3	红灯亮	绿灯亮	25<br>
State4	红灯亮	黄灯亮	5<br>
<br>
