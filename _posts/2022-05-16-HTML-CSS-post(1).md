---
toc: true
layout: post
description: 자바스크립트
categories: [HTML/CSS]
title: HTML/CSS 팁(1)
---
# Layout
## display: none vs visiblity: hidden
display: none의 경우 dom 에는 로드됨, 화면에 보이지 않음, 화면에서는 공간을 차지하지 않음
visiblity: hidden의 경우 화면에 보이지 않지만 실제로 공간을 차지하고 있음

## absolute 기준
X축의 경우 absolute(본인) ---기준---> ①absolute (부모) or ②relative (부모/조상)
Y축의 경우 absolute(본인) ---기준---> relative(부모/조상)

## Outerheight
div에 쓸 수 있음
