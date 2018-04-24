---
title: CFD
subtitle: 数値流体力学（CFD）
comments: false
---

# CFDを用いた研究
本研究室ではCFD (Computational Fluid Dynamics 数値流体力学）のコードを用いて、様々な流動の研究を実施しています。

## 浮遊液滴の回転振動挙動
地上で液滴を浮遊させるためには、何らかの外力が必要となりますが、液滴の挙動にはその影響が現れます。超音波を利用する手法では、圧力定在波の節の位置に液滴が保持されることを利用しますが、表面近傍の薄い層には、周囲と位相の異なる流れが誘起されることがわかりました［1］。Fig.1は、超音波の1周期の間での表面近傍の流れの変化を示したもので、左側の青い部分が液滴内部、右側の赤い部分が周囲の気体です。表面流は時間帯によっては、周囲の流れに対し逆流になっていることがわかります。

Fig.2は、回転により形状が変化する様子を示したものですが、アレイ状になってからの回転数と伸びの関係は実験で得られているものとよく一致することがわかりました [2]。

| ![Fig.1](/img/Fig7.png "Fig.1 Analysis of levitated liquid droplet: Surface flow on droplet in acoustic standing wave") |
|------|
| Fig.1 Analysis of levitated liquid droplet: Surface flow on droplet in acoustic standing wave |

| ![Fig.2](/img/Fig8.png "Fig.2 Analysis of levitated liquid droplet: Shape variation of rotating droplet") |
|------|
| Fig.2 Analysis of levitated liquid droplet: Shape variation of rotating droplet |


![液滴](/img/drop.png)

## PTSの数値解析
原子炉において何らかの事故が発生し、高温高圧条件下にある圧力容器に非常用冷却水が注水されることで発生する熱衝撃をPTS (Pressurised Thermal Shock)と言います。PTSによって圧力容器壁面上のクラックに引張応力が作用した時、圧力容器が破損する事が懸念されます。

本研究室では、健全性評価のための構造解析に必要な温度分布を、DESと呼ばれる乱流モデルを用いた熱水力数値解析をによって、比較的高精度・低コストで求める事を目的としています。

## 過熱ジェットに対する輻射モデルの影響検討
原子炉の過酷事故（シビアアクシデント）時には高温の蒸気が噴出することが考えられます。本解析では高温の過熱ジェットによる周囲の気体の加熱に対する輻射の影響を検討しました。下図は解析によって得られた温度分布を示しています。

![輻射](/img/T-cont.jpg)

[1] T. Watanabe, ”Numerical Simulation of oscillating flow field including a droplet,” Int. J. Multiphysics, 7(2013)19-30.
[2] T. Watanabe, ”Deformation of a rotating two-lobed droplet,” Int. J. Mathematical Models and Methods in Applied Sciences, 10(2016)179-184.
