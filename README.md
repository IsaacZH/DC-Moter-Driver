<div align="center">
  
# DC-Motor-Driver
<a href="./LICENSE"><img alt="License" src="https://img.shields.io/badge/License-MIT-yellow"></a>
[![Email](https://img.shields.io/badge/Email-1812924685@qq.com-green)](mailto:1812924685@qq.com)

![](https://raw.githubusercontent.com/IsaacZH/FigureBed/master/%E7%94%B5%E6%9C%BA%E6%AD%A3%E8%BD%AC.png)

</div>

<br>

--------

<br>

# 实现功能
- 支持15V-50V电压输入，通过BUCK芯片降压到12V驱动电机和芯片。
- 通过半桥驱动芯片控制H桥，可控制电机转速和正反转。
- 内部集成PWM生成，可直接在控制板上手动调节电机转速。
- 可切换为外部控制，通过单片机输入电平信号控制半桥芯片。

# 原理图
![](https://raw.githubusercontent.com/IsaacZH/FigureBed/master/%E7%AC%AC%E4%BA%8C%E7%89%88%E8%AE%BE%E8%AE%A1%E5%8E%9F%E7%90%86%E5%9B%BE.png)
![](https://raw.githubusercontent.com/IsaacZH/FigureBed/master/PWM%E5%8E%9F%E7%90%86%E5%9B%BE.png)
# 功能演示
### DC-DC测试
<div align="center">
  <tr>
    <td><img src="https://raw.githubusercontent.com/IsaacZH/FigureBed/master/%E7%94%B5%E5%8E%8B%E8%BE%93%E5%87%BA%20(4).png" alt="图片1" width="48%"></td>
    <td><img src="https://raw.githubusercontent.com/IsaacZH/FigureBed/master/%E7%94%B5%E5%8E%8B%E8%BE%93%E5%87%BA%20(3).png" alt="图片2" width="48%"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/IsaacZH/FigureBed/master/%E7%94%B5%E5%8E%8B%E8%BE%93%E5%87%BA%20(2).png" alt="图片3" width="48%"></td>
    <td><img src="https://raw.githubusercontent.com/IsaacZH/FigureBed/master/%E7%94%B5%E5%8E%8B%E8%BE%93%E5%87%BA%20(1).png" alt="图片4" width="48%"></td>
  </tr>
</div>

### PWM生成测试
<div align="center">
  <tr>
    <td><img src="https://raw.githubusercontent.com/IsaacZH/FigureBed/master/PWM%E8%BE%93%E5%87%BA%20(3).png" alt="图片1" width="48%"></td>
    <td><img src="https://raw.githubusercontent.com/IsaacZH/FigureBed/master/PWM%E8%BE%93%E5%87%BA%20(2).png" alt="图片2" width="48%"></td>
  </tr>
</div>

### 内部驱动演示
https://github.com/user-attachments/assets/b377bf6a-9149-48c2-a46a-859bd3c1f100
