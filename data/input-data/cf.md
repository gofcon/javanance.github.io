# CF

Raw데이터를 GMV내에 코드로 코드변환작업 및 각 변동스텝별 현금흐름을 회계정보 산출에 유용한 형태로 ETL처리를 수행한다.  작업 순서에 따라 LV1, LV2, LV3, LV4로 구분된다.&#x20;

IFRS 17의 변동분석을 수행하기 위해서는 직전 결산에 사용된 CF와 현재 결산 기준의 최종 CF를 비롯해 직전 기준에서 해당 결산까지 변동을 구분하여 보고자 하는 사유별로 나누어 출력한 CF set가 필요하다.  최소한의 구분을 나누면 아래와 같다. 변동분석의 순서 및 변동스텝의 세분화는 기준서에 명시되어 있지 않으며,  항목별 변동성을 줄이기 위해서는 기시부터 기말까지의 변동을 가장 적은 수준의 변동폭으로 설명할 수 있도록 순서를 구성하는 것이 바람직하다.

* 전기결산 부채 평가에 사용된 기말 현금흐름 (전기말 가정, 전기말 할인율)
* 신규 물량 효과&#x20;
* 물량차이 효과
* 계리적 가정변경 효과
* 금융 가정변경 효과
* 재량 변경 효과 (= 당기 결산 부채 평가에 사용된 기말 현금흐름)

{% hint style="success" %}
**CF : 이행현금흐름**

* CfLv1Goc
* CfLv2Delta
* CfLv3Real
* CfLv4Df
{% endhint %}

## CF\_LV1\_GOC
