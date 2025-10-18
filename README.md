用法  bash nepalscan-batch  192.168    默认就扫描192.168.0.0/16的高危端口
Usage: bash nepalscan-batch 192.168 by default scans high-risk ports of 192.168.0.0/16

<img width="1026" height="489" alt="image" src="https://github.com/user-attachments/assets/70486ee0-1b95-4f44-825c-0bc149314e6b" />



如果是非交互式shell 如哥斯拉的cmd 窗口  则最好将结果追加输出  bash nepalscan-batch  192.168 >192.168.txt

If it is a non-interactive shell, such as Godzilla's cmd window, it is best to append the output. bash nepalscan-batch 192.168 >192.168.txt


扫描示例

Scan Example

<img width="555" height="299" alt="image" src="https://github.com/user-attachments/assets/8b81428f-a1ee-470f-bc9e-aa2909f88ab9" />


**适用场景**

Applicable Scenarios

fscan等二进制被agent检测到了导致无法运行，如下图，或者是魔改的fscan被检测到了，能运行，但是不一会就被agent 杀掉，或者是防守方严格盯屏的严苛场景

The fscan and other binaries were detected by the agent and could not run, as shown in the picture. Alternatively, a modified fscan was detected, could run, but was killed by the agent after a short while, or it was a strict scenario where the defender was closely monitoring the screen.
下图为fscan被禁止：  

The following figure shows fscan is disabled:
<img width="759" height="183" alt="image" src="https://github.com/user-attachments/assets/fb1d22ca-882b-4d86-b246-40993cf28542" />


下图为魔改的fscan   加敏感参数被禁止运行     以及不加敏感参数 被   agent exit掉:             

The following figure shows that the modified fscan is prohibited from running with sensitive parameters and is exited by the agent without sensitive parameters.:



<img width="1161" height="954" alt="image" src="https://github.com/user-attachments/assets/2ca8adf8-a57f-4270-b0ce-cc3a3c79400a" />

