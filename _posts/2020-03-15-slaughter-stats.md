---
layout: post
title: "도축 통계"
date: 2020-03-15 00:00:00 +0900
observable: "https://api.observablehq.com/@kkyueing/slaughter-statistics.js?v=3"
---
## 개요

2004년 1월부터 2020년 12월 사이 이후 전국의 소, 돼지, 말, 양, 닭, 오리를
도축하는 도축장(도계장)의 도축검사실적, 도축실적 보고내용을 집계했어요.

출처는 농림축산검역본부의 [도축실적
통계](http://www.qia.go.kr/livestock/clean/listTcsjWebAction.do?clear=1)입니다.
정리된 데이터는
[깃헙](https://github.com/veganstudies/stats/blob/master/slaughter-kr.csv)에
공유했어요.

## 요약

<div id="ob-summaryDescription" class="ob-block"></div>

## 통계

가장 많이 죽임을 당하는 동물은 **닭**입니다.

<div id="ob-viewof-filter" class="ob-block"></div>

<div id="ob-stackedBarChart" class="ob-block"></div>

도살 당하는 닭의 수가 너무 많아서 다른 동물들의 통계는 보이지 않을 정도입니다.
선그래프로 바꾸고 y축을 로그 스케일로 변환하면 다른 종의 동물들도 좀 더 잘
확인할 수 있어요.

<div id="ob-lineChart" class="ob-block"></div>

다음은 2004년 기준 증가/감소 추이를 보여주는 그래프입니다. 2004년을 100으로
놓았을 때 매년 얼마나 늘거나 주는지 볼 수 있어요. **양**은 2012년까지 약 1만
마리 수준이었는데 2013년에 약 6만 마리로 증가한 이후 꾸준히 늘어 2020년에는
약 17만 마리가 되었습니다. 2004년에 비해 약 17배 증가한 규모입니다.

<div id="ob-indexChart" class="ob-block"></div>

## 통계에 포함되지 않은 동물들

위 계산에는 도축장/도계장에서 먹기 위해 죽인 소, 돼지, 말, 양, 닭, 오리만을
포함하고 있습니다. '도살두수'는 생체검사두수에서 도살금지두수를 제외한
수치입니다. 즉, 먹기에 적합하다고 판정한 후 도축장/도계장에서 죽인 동물의
수입니다. 따라서 태어나서 바로 죽임 당하는 수평아리 등은 계산에 포함되어 있지
않습니다.

물살이나 다양한 무척추 동물도 포함되지 않았습니다. 먹기 위해 죽인 동물이 아닌
실험 동물 등도 포함되지 않았습니다.

## 마치기 전에

<div id="ob-deathSinceOnPage" class="ob-block"></div>

## 관련글

* \<[우리는 왜 개는 사랑하고, 돼지는 먹고, 소는
  신을까](/2020/02/22/why-we-love-dogs.html)\> 요약
* \<[동물 해방](/2019/07/28/animal-liberation.html)\> 요약
* [다양한 동식물의 의식경험](/2019/10/22/sentience-table.html)
