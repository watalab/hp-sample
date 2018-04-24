---
title: System analysis
subtitle: システム解析
comments: false
---

# 原子炉事故時の熱水力挙動
代表的な安全解析コードであるTRACを用いた電源喪失事故の解析では、炉心溶融までの熱水力挙動を、よく再現できることを示し、運転員操作のタイミングや時間余裕の検討を行いました［1］。これに基づき、格納容器内の圧力上昇についての検討を進め、外部からの冷却と破損による格納容器からの漏洩の影響について明らかにしました［2］。Fig.1は、格納容器の圧力変化を示したものですが、漏洩と冷却のいずれを仮定しても圧力上昇は緩やかになること、炉内の熱流動現象には大きな影響を及ぼさないこと等がわかりました。

Fig.2は、蒸気発生器伝熱管破断事故の際の低温側配管での注入水による温度低下を、安全解析コードRELAP5により調べたものです[4]。ここでは、低温側配管と同時に上部プレナムに注入する効果を調べており、ベースケースでは両方有り、ケースIでは、配管のみ、ケースIIでは、両方無し、ケースIIIでは、上部プレナム分を配管に上乗せして注入、という条件を検討しています。この解析により、上部プレナム注入の効果が小さいこと、配管注入のみで、温度は大きく低下することなどが明らかになりました。

| ![Fig.1](/img/Fig1.png "Fig.1 Analysis of station blackout accident: Containment pressure") |
|------|
| Fig.1 Analysis of station blackout accident: Containment pressure |

| ![Fig.2](/img/Fig2.png "Fig. 2  Analysis of steam generator tube rupture accident: Cold-leg fluid temperature in broken loop") |
|------|
| Fig. 2  Analysis of steam generator tube rupture accident: Cold-leg fluid temperature in broken loop |

# 蒸気発生器での自然循環挙動
Fig.3は、RELAP5によって得られたループ流動の解析結果を境界条件として行った三次元流動解析の結果の一部で、伝熱管群の入り口付近の温度分布と速度ベクトルを示したものです。ループ全体では自然循環が成立している条件でも、一部の伝熱管で逆流や停滞が起こることが確認され、また、細い伝熱管の内部に上昇流と下降流が同時に現れることもわかりました。自然循環の安定性は、これまで考えられていたような、管毎の単純な順流、逆流現象ではなく、複雑な流動現象であることが明らかになりました。

| ![Fig.3](/img/Fig6.png "Fig. 3 Analysis of steam generator flow instability: Temperature and velocity distributions") |
|------|
| Fig. 3 Analysis of steam generator flow instability: Temperature and velocity distributions |


[1] 渡辺他、”BWR全電源喪失事故の解析　福島第1発電所2号機における炉心損傷までの熱水力挙動”、日本原子力学会和文論文誌、10 (2011) 240-244. 
[2] T. Watanabe, et al., “Analysis of BWR long-term station blackout accident using TRAC-BF1,” Annals of Nucl. Energy, 49 (2012) 223-226.