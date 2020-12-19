## ��HT66F318 For Arduino NANO
* HOLTEK HT66F318 28SSOP Pin assignment for Arduino Nano applications.<br>
�Q��HT66F318 28SSOP ���NArdunio Nano ��{�b�q�ƤW������!!!(�ȴ���Pin���N��z�ϨëD�i�H�����ۮe)<br>
�b���Q�ϥ�Arduino�Υu�O��²�����ΩΤj�q����, �����������Ҽ{��, �Y�i�H�ۤv�s�y²�檺���θ˸m.<br>
HT66F318 4K flash, HT66F319 8K flash pin to pin

### For example:
* Project Option:<br>
HXT (External 8MHz X'tal); : �i�ﶵ��:HXT(400K~16Mhz),HIRC4M,HIRC8M,HIRC12M<br>
LICR (Low speed internal RC for TB0/TB1); �i�ﶵ��:LXT(32.768Khz),LIRC(32Khz)<br>

* WatchDog: enable/disable<br>

* UART port<br>

* Time base timer (TB0,1) enable LIRC interrupt<br>

* Timer Module (TM0) enable HXT interrupt for 200us<br>

* ADC�]�m�����z�LAN0~AN7Ū���~����J,��AVDD,AVDD1/2,AVDD1/4Ū��������J.

* PWM��X
PWM(HT66F317)�]�m�����z�LTP0, TP1��X, TM0/TM1(16bit), �̤j�]�mTM0/TM1(16bit)
PWM(HT66F318)�]�m�����z�LTP0, TP1, TP2��X, TM0(hi-16bit), �̤j�]�mTM1(10bit), TM2(hi-16bit)

* ��J�T������ [�q��_pb3/TP2(TM2) PWM�ζq��_pb1 test outpt]
Capture(HT66F317)�]�mTP1���J����16bit+16bit counting
Capture(HT66F318)�]�mTP1���J����10bit+16bit counting

* HT-IDE3000 HT66F317/HT66F318 28ssop with HT-IDE3000 & e-Link & e-WriterPro<br>
���[HT66F318 Document](https://www.holtek.com.tw/search?key=ht66F318)<br>
����&����Development & Debug[IDE3000 & ICE](https://www.holtek.com.tw/web/guest/ice)<br>
�N�J��Progrmming & writer[HOPE3000 & e-WriterPro](https://www.holtek.com.tw/web/guest/programmer)<br>

### Relevant information
* HT-IDE3000 V8.02
![Image](HT-IDE3000_version.jpg)
* HOLTEK C Compiler V3/Assembly
![Image](ProjectCompiler.jpg)
* HT66F318 Config
![Image](ProjectOption1.jpg)
![Image](ProjectOption2.jpg)
![Image](ProjectOption3.jpg)
![Image](ProjectOption4.jpg)
* HT66F318 28ssop Schematic Diagram 
![Image](CircuitDiagram.jpg)

* �Ѧҭ�z��(part) & Arduino Nano Define
![Image](ArduinoNanoDefine.jpg)
![Image](MCUdiagram.jpg)

