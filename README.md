# pybricks-stubs
pybricks-stubs包为python+VSCode程序开发环境(lego ev3 for bricks-micropython)提供pybricks类方法等提示功能。
这个包不支持在PC或机器人运行代码。这个包仅提供在PC上键入python代码时的pybricks代码提示功能。

VSCcode的安装方法（在VSCode终端中键入）    
py -3 -m venv .venv  
.venv\Scripts\activate   
python -m pip install --upgrade pip      
pip install pybricks-stubs    

验证安装
pip list                            

This package is meant to provide typings (and IntelliSense) to those developing Python programs for the LEGO<sup>&reg;</sup> MINDSTORMS<sup>&reg;</sup> EV3 with the official LEGO<sup>&reg;</sup> software ([pybricks](https://education.lego.com/en-us/support/mindstorms-ev3/python-for-ev3)). All typings are based on the [LEGO<sup>&reg;</sup> API](https://le-www-live-s.legocdn.com/sc/media/files/ev3-micropython/ev3micropythonv100-71d3f28c59a1e766e92a59ff8500818e.pdf).
This package does not support executing robot code on the computer or on the robot. This package does provide type hinting while writing Python code on the computer for later upload/deployment to the robot. 

