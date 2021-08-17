วิธีรัน 
    ลง library
        pip install PyAutoGUI
        pip install pynput
    รันโปรแกรม
        python .\autoclicker.py
        
        กด f1 เริ่มคลิก
        กด f2 หยุด
        กด f3 ออกจากโปรแกรม
วิธีปรับความเร็ว บันทัดที่ 5 คำว่า delay = <ใส่ค่าเข้าไป>
 
# python-autoclicker
A simple autoclicker with controls using pyautogui. 
![Image](https://i.imgur.com/QIh8yAA.png)

Default delay is 1 second.

**Note:**  
As a fail-safe, moving your mouse to the very top left corner will exit the program.


# Controls

Key | Action
--- | ---
F1 | Resumes the autotyper
F2 | Pauses the autotyper
ESC | Exits the program

If you want to change the shortcut keys, change their values with the keycodes provided here:
https://pythonhosted.org/pynput/keyboard.html


# Future Enhancement
* GUI
