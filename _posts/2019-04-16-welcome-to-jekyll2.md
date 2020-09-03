---
layout: post
title:  "BOF"
description: let's find out about bof
tags: BOF
---

BOF란 Buffer Overflow의 약자로 프로그래밍에서는 프로세스가 데이터를 버퍼에 저장할떄 지정한 곳을 넘어서 저장하는 것을 의미한다.

일반적으로 BOF는 c와 c++에서 자주 일어나는데 그 이유는 
>메모리에서 내장된 데이터 접근 또는 덮어쓰기 보호기능을 제공 X 

>배열에 기록되는 데이터가 그 배열의 범위 안에 포함되는지 자동으로 검사 X

이러한 이유로 다른 언어들 보다 c와 c++에서 BOF가 자주 일어난다

