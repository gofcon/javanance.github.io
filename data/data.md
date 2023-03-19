---
description: 'Table : Entity'
---

# Data Mart 개요

IFRS 17의 회계정책에 따른 회계정보생성 및 분개 처리를 위해 필요한 Data Mart .  크게 Input , Output ,  master 로 구성됨.&#x20;

{% hint style="info" %}
entity의 특성으로 구별 시 크게 아래와 같음.

* INPUT&#x20;
  * **Raw**
  * **Ncont**
  * **Cf** : Fulfilment cash flow 명목금액&#x20;
  * **Df** : 할인계수 (최초, 직전, 현행, 체계적배분 등 필요 할인계수)
  * **TVOG / RA** : TVOG, RA를 별도의 session에서 산출하는 경우&#x20;
  * **Ratio**
* OUTPUT
  * **Box**
  * **Rst**
* MASTER
  * **Map**
  * **Mst**
{% endhint %}
