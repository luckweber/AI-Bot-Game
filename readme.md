
# Initital Command

```
pip install -r requirements.txt
pip freeze > requirements.txt 
````
https://towardsdatascience.com/snake-played-by-a-deep-reinforcement-learning-agent-53f2c4331d36

# Auto Click pyautogui

[Link site](https://pyautogui.readthedocs.io/en/latest/index.html)
```
pyautogui.click()  
pyautogui.moveTo(100, 200)
pyautogui.click(x=2112, y=870,button='right')
x,y = pyautogui.locateCenterOnScreen('Screenshot_1.png')
pyautogui.click(pos, duration=0.25)
pyautogui.locateOnScreen(imPath('you_failed.png'))

```