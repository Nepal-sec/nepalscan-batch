<img width="1026" height="489" alt="image" src="https://github.com/user-attachments/assets/70486ee0-1b95-4f44-825c-0bc149314e6b" />

用法  bash nepalscan-batch  192.168    默认就扫描192.168.0.0/16的高危端口

如果是非交互式shell 如哥斯拉的cmd 窗口  则最好将结果追加输出  bash nepalscan-batch  192.168 >192.168.txt



扫描示例
<img width="555" height="299" alt="image" src="https://github.com/user-attachments/assets/8b81428f-a1ee-470f-bc9e-aa2909f88ab9" />



适用场景：形如 fscan等2进制被 agent检测到了   不能运行，或者魔改fscan  时  进程被检测到了直接被exit掉    亦或者有防守队盯屏幕，看告警的严苛环境


下图为fscan 不能使用的情形
<img width="759" height="183" alt="image" src="https://github.com/user-attachments/assets/e4c73452-dd17-4495-a9d7-5467608f62d6" />




