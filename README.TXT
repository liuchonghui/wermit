C-KERMIT 10.0 DEVELOPMENT

C-Kermit 10.0 Beta.06 14 October 2022

Beta.06 fixes a couple problems in Beta.05 and adds numerous
improvements for (Open)VMS from SMS.  For details see:

  https://www.kermitproject.org/ckupdates.html

which contains an account of all the previous development
versions, Alphas, and Betas since C-Kermit 9.0 was released
in 2011.

=========================加自定义=========================
1.将ttyusb0.rc和ttyacm1.rc拷贝到home下，即 cp *.rc ~/
2.编译，执行：make linux
3.执行：wermit --rc ttyusb0.rc   会在执行目录生成ttyUSB0.log串口日志
4.执行：wermit --rc ttyacm1.rc   会在执行目录生成ttyACM1.log串口日志
5.连接串口，执行connect
6.停止串口，执行Ctrl+\再按下c 回到commandline模式，按下q退出
==========================================================
