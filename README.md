# reaper-pomodoro: Pomodoro timer for Reaper
[![Donate](https://img.shields.io/badge/donate-paypal-orange.svg)](https://paypal.me/evgazloy)  

![Screen_1](https://i.ibb.co/PDvpWBh/main-full.png)  

[Read about pomodoro technique](https://en.wikipedia.org/wiki/Pomodoro_Technique)  

## Manual installation  
1. Open the REAPER resource folder by opening REAPER and then selecting Options > "Show REAPER resource path in explorer/finder..." from REAPER's menu bar.
2. [Download the script.](https://raw.githubusercontent.com/evgazloy/reaper-pomodoro/main/vo_pomodoro.lua)
3. Move vo_pomodoro.lua file into the Scripts directory that you opened in step 1.

## Open  
You can find the script in action list:  
![Action](https://i.ibb.co/BLzB0ZM/actions.png)

### Launch on startup  
Requirements: [SWS Extension](https://www.sws-extension.org/)  

Copy vo_pomodoro.lua script ID:  

![id](https://i.ibb.co/dQwmmf1/copy.png)  

Set global or project startup action:  

![startup](https://i.ibb.co/NZ0pHVK/set.png)

Paste script ID:  
![id](https://i.ibb.co/hHyw1NX/id.png)  

![success](https://i.ibb.co/9cfYrg2/success.png)

## Usage  

![Screen_2](https://i.ibb.co/Z8Cr1tF/main.png)  

Click on countdown to start working period

![work](https://i.ibb.co/zNFkqCV/progress.png)  

You can skip current period or reset timer by right click:  

![skip](https://i.ibb.co/Y0Mv8yS/skip.png)

### Settings  

![settings](https://i.ibb.co/bK5Vh4L/settings.png)

- Work - Working interval duration (min)
- Short - Short break duration (min)
- Long - Long break duration (min)
- Count - Number of periods before long break  

Click and Drag vertically to change the values  

Click Save to apply changes:  

![save](https://i.ibb.co/thQKXqv/save.png)

### Placement
By default the script is located in Docker.  
If you moved it to floating window, click on Dock to place timer in Docker:

![dock](https://i.ibb.co/GMtFgmv/dock.png)
