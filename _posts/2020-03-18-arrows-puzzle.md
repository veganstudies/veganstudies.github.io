---
layout: post
title: "화살표 퍼즐 게임"
date: 2020-03-18 00:00:00 +0900
observable: "https://api.observablehq.com/@kkyueing/arrows-puzzle.js?v=3"
---
## 개요

화살표 퍼즐 게임은 화살표를 이어 붙여서 우측 상단의 목적지에 최대한 가깝게 가는 게임입니다. 화살표를 클릭하면 해당 화살표가 선택됩니다.

* 각 화살표는 **정책**입니다.
* X축으로 가깝게 갈수록 **인종 차별**이 개선됩니다.
* Y축으로 가깝게 갈수록 **계급 차별**이 개선됩니다.

## 게임

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

'완료'를 체크하면 결과 화면을 드래그해서 회전시킬 수 있습니다. 화면을 회전시키면 숨어 있던 Z축이 나타나요. Z축은 **젠더 차별**입니다.

<div id="ob-viewof-done" class="ob-block"></div>

존재하는 축을 고려하지 않고 의사결정을 하면 필연적으로 나타나는 결과입니다.
