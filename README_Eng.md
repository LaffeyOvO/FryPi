<p align="right">
  <a href="./README.md">中文</a> | <b>English</b> 
</p> 


<h1 align="center">FryPi</h1>

<div align=center>
        <img src=https://img.shields.io/badge/version-1.1-blue>
        <img src=https://img.shields.io/badge/License-GPL3.0-green)>
        <img src=https://img.shields.io/github/stars/No-Chicken/FryPie-F411DevKit.svg>
</div>

<h3 align="center">STM32F411RET6 DevKit</h3>

<p align="center">
	<img style="border: 2px solid #ccc; border-radius: 30px; padding: 0px;" width="50%" src="./2.software/2.Advanced/6.LVGL-SmartWatch/images/LVGL演示.gif"><img style="border: 2px solid #ccc; border-radius: 30px; padding: 0px;" width="50%" src="./2.software/2.Advanced/3.Thermal-camera-gesture-recognition/images/手势识别演示.gif">
</p>
<p align="center">
	<img style="border: 2px solid #ccc; border-radius: 30px; padding: 0px;" width="50%" src="./2.software/2.Advanced/2.MNIST-Handwritten-number-recognition/images/MNIST演示.gif"><img style="border: 2px solid #ccc; border-radius: 30px; padding: 0px;" width="50%" src="./images/在环开发.jpg">
</p>




<p align="center">
	<a href="https://space.bilibili.com/34154740">Bilibili </a> |
	<a href="https://www.bilibili.com/video/BV19g4y1N7YR/">video </a> |
    <a href="https://oshwhub.com/no_chicken">hardware </a> 
</p>


## :ledger: Overview

This is a STM32F411RET6 mini development board, which can be used for AI development, UI development, digital power control board, etc. And can even be used for your other projects.

<p align="center">
	<img style="border: 0px solid #ccc; border-radius: 20px; padding: 0px;" width="30%" src="./images/Core_V1.1后视图.jpg"><img style="border: 0px solid #ccc; border-radius: 20px; padding: 0px;" width="30%" src="./images/Core_V1.1前视图.jpg">
</p>
The original purpose of making this board is because of the previous smartwatch project [OV-Watch](https://github.com/No-Chicken/OV-Watch)，many copy people said that the device is very difficult to weld, secondary development is not convenient, In addition, I also plan to deploy some AI-related things on STM32 and do a tutorial, so the FryPi fried chicken pie was born. This development board is not only suitable for beginners, but also for advanced developers, and advanced demos may require a certain knowledge reserve.

## :rocket: Features

  - MCU use STM32F411RET6, Cortex-M4 core with DSP and FPU, 512 Kbytes of Flash memory, 100 MHz CPU, ART Accelerator.
  - External SPI Flash can be welded in addition.
  - Rich Demo: [smart watch](https://github.com/No-Chicken/FryPi/tree/master/2.software/2.Advanced/6.LVGL-SmartWatch), [thermal gesture recognition](https://github.com/No-Chicken/FryPi/tree/master/2.software/2.Advanced/3.Thermal-camera-gesture-recognition), [handwritten number recognition](https://github.com/No-Chicken/FryPi/tree/master/2.software/2.Advanced/2.%20MNIST-Handwritten-number-recognition), develop with matlab, [simulink HIL development](https://github.com/No-Chicken/FryPi/tree/master/2.software/2.Advanced/5.simulink-Co-develope) and so on.
  - Leave the port for external expansion board. (For example, the top demo .gif showed is pluged the Cam expansion board into the Core board)
  - There are dual TypeC and single TypeC versions of the Core board.

## :package: Get Started

After the development board is welded, once the [template demo](https://github.com/No-Chicken/FryPi/tree/master/2.software/1.Basic/0.template) is donloaded, if there is no problem with the hardware, the phenomenon is: then the TypeC corresponding to the serial port is connected to the computer, L2 will blink, press the Key to switch mode, L2 blink frequency will change, and the upper PC will receive the mode information;

<div align=center>
	<img style="border: 2px solid #ccc; border-radius: 30px; padding: 0px;" width="50%" src="./2.software/1.Basic/0.template/images/开机测试.gif" /><img style="border: 2px solid #ccc; border-radius: 20px; padding: 0px;" src="./2.software/1.Basic/0.template/images/上位机.jpg" width="24%"/>
</div>

If the TypecC connected to the USB of the development board is connected to the computer, the computer will appear formatted U disk, and then after formatting, it will simulate a U disk.

<div align=center>
	<img src="./2.software/1.Basic/0.template/images/格式化.jpg" width="35%"/>
</div>
Details can be found in the demo: [template demo](https://github.com/No-Chicken/FryPi/tree/master/2.software/1.Basic/0.template).

## ✨Contributors

<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="16.66%">
          <img src="https://avatars.githubusercontent.com/u/85883051?v=4" width="100px;" alt="kingham"/><br /><sub><b>kingham</b></sub></a><br /><a title="Code">💻</a> <a title="Documentation">📖</a> <a title="Tests">⚠️</a> <a title="Reviewed Pull Requests">👀</a></td>
<td align="center" valign="top" width="16.66%">
          <img src="https://avatars.githubusercontent.com/u/109140632?v=4" width="100px;" alt="lantian"/><br /><sub><b>lantian</b></sub></a><br /> <a title="Code">💻</a> <a title="Tests">⚠️</a> <a title="Ideas, Planning, & Feedback">🤔</a> <a title="Bug reports">🐛</a></td>
    </tr>
  </tbody>
</table>
