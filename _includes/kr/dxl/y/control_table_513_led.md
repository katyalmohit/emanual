LED를 ON/OFF 합니다.

| 값    |  LED 동작             |
| :---: | :------------------: |
| 0     | 장치 뒷면의 LED를 끔  |
| 1     | 장치 뒷면의 LED를 켬  |


{% capture LED %}
**참고** : 장치의 상태(조건)에 따른 LED의 동작입니다.

| 상태        | LED 동작  |
|:-----------:|:--------:|
| 부팅        | 1회 점멸  |
| 공장 초기화  | 4회 점멸  |
| 알람        | 점멸      |
| 부트 모드   | 점등      |
{% endcapture %}

<div class="notice">{{ LED | markdownify }}</div>