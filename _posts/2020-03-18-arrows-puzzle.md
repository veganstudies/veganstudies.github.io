---
layout: post
title: "화살표 퍼즐 게임"
date: 2020-03-18 00:00:00 +0900
observable: "https://api.observablehq.com/@kkyueing/arrows-puzzle.js?v=3"
---
## 개요

출발지(붉은 점)에서 화살표를 이어 붙여 목적지(녹색 점)에 최대한 가깝게 가는 게임입니다. 화살표를 클릭하면 해당 화살표가 선택됩니다.

* 각 화살표는 **정책**입니다.
* 오른쪽으로 갈수록 **인종 차별**이 개선됩니다.
* 위로 갈수록 **학력 차별**이 개선됩니다.

아래 화면에서 화살표를 클릭해서 선택하세요.

<div id="ob-canvasArrows" class="ob-block"></div>

화살표를 모두 선택했으면 아래의 해설을 읽어주세요.

<div id="ob-coveredResult" class="ob-block"></div>

<div style="display: none;">
<div id="ob-clickHandler" class="ob-block"></div>
<div id="ob-updateOnSelections" class="ob-block"></div>
<div id="ob-selections" class="ob-block"></div>
</div>

## 해설

'완료'를 체크하면 결과 화면을 드래그하여 회전하거나 확대/축소할 수 있습니다. 화면을 움직이면 숨어 있던 Z축이 나타나요. Z축은 **젠더 차별**입니다.

<div id="ob-viewof-done" class="ob-block"></div>

이 게임에서 X축의 인종 차별과 Y축의 학력 차별은 본인이 서 있는 위치에서도 눈에 쉽게 보이는 차별입니다. 즉 본인의 사회적 위치로 인해 쉽게 인식할 수 있는 차별을 뜻해요.

Z축은 화면을 돌리기 전까지는 눈에 보이지 않는 차별입니다. 즉, 본인의 사회적 위치로 인해 인식하기 어려운 차별을 뜻해요.

본인이 인식하고 있는 차별들을 없애기 위해 열심히 노력했지만 결과가 만족스럽지 않습니다. 존재하는 축을 고려하지 않고 의사결정을 하면 필연적으로 나타나는 결과입니다.

본인은 어떤 사회적 위치에 서 있는지, 어떤 차별을 쉽게 인식하고 어떤 차별을 쉽게 인식하지 못하는지 생각해보면 좋겠습니다.
