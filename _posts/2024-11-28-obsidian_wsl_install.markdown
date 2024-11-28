---
layout: post
title:  "Obisian을 wsl2에서 실행시키는법"
date:   2024-11-28 16:00:00
author: Inchul Baek
categories: Obisidian
tags: PID, 제어
---

Obisidian을 wsl2 에 설치하는 방법

원본 주소
- https://forum.obsidian.md/t/support-for-vaults-in-windows-subsystem-for-linux-wsl/8580/49


step1. linux용 obsidian 설치

wget https://github.com/obsidianmd/obsidian-releases/releases/download/v1.4.13/obsidian_1.4.13_amd64.deb
sudo apt-get install -y ./obsidian_1.4.13_amd64.deb

step2. 쉘에 아래명령을 쳐서 옵시디언 실행
/>obsidian 


step3. 만약 한글이 깨진다면 wsl에 한글폰트 설치 
sudo apt-get install fonts-nanum*
로케일설정
sudo dpkg-reconfigure locales

출처 : https://datanavigator.tistory.com/60
