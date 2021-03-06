# RO M : NextGeneration Fishing

This is an auto fishing robot for Ragnarok Online Mobile : New Generation. It is only support Windows(Emulator) now, but technically, it shuold support all the OS.

## Installation

### Prerequisites

If you are Windows users, you are able to skip this part and execute the pre-build version.

`pip install pyautogui, pynput`

### Pre-build

Download the zip file from release.

### Using source code

The program is writen by Python 3, please make sure you have installed Python and dependencies first.

```shell
git clone https://github.com/Ronaldzzzzz/ROM_NextGeneration_Fishing
cd ROM_NextGeneration_Fishing
python main.py
```

## How to use

* Using an emulator and let your character be ready for fishing, which means the casting button is ready to be clicked. If you need to use another fishing bait, you also need to change at this step.
  
* Running `RO_Fishing.exe`, using mouse middle key to select the range of the game, **press** at the left top corner and **release** at the right bottom corner (aka drag). **(Do not select the emulator windows. ONLY select the game)**
  
* Press `Enter` in the program, the program will move your mouse position to the fishing button.
  
* Press `Enter` again, and the program will start fishing in a 3 seconds delay.

---

* 將模擬器角色移動至釣魚區域，換好魚餌，並按下釣魚鍵直到拋竿按鈕出現
  
* 開啟`RO_Fishing.exe`後，使用滑鼠中鍵框遊戲的視窗，左上按下然後拉到右下放開 **（只需要框遊戲的視窗，模擬器的視窗不要框到）**
  
* 按下`enter`後，游標會移動到釣魚按鈕上
  
* 再次按下`enter`，程式等待3秒，之後即開始自動釣魚

## Need to be fixed

* Simplify the process
* Improve the detection, or finding a better confidence value

## Author

Ronald Lin - jacky7770123@gmail.com
