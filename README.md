제작자의 허락없이 상업적 목적으로 배포하거나 개조하여 배포할경우 저작권법 위반으로 처벌받으실수 있습니다.

제작자 : taeho070607 

**어떠한 경우에서도 불법적인 목적으로 사용될경우 제작자 본인과는 관계없으며 처벌받으실수 있습니다.**

# 설명

1. 이 악성코드는 완전히 침입자의 정보를 없앨수있습니다.
기본적으로 이 악성코드는 일반적인 공격자와 피해자의 연결방식이(TCP) 다르기 때문에 절대 공격자의 정보가 노출될수없습니다.
악성코드 -> 디스코드웹훅 -> 디스코드 -> 공격자
의 연결방식을 사용하고 혹시나 디스코드의 협조로 인한 위협또한
악성코드 -> 디스코드웹훅 -> 디스코드(일반적인 계정이아닌 익명계정 *익명이메일*) -> 토르 -> 공격자
계정을 접속할때 vpn 없이 접속하면 공격자의 정보가 디스코드에 남지만 vpn을 사용한다면 알수없습니다.
그리고 지속적인 연결이아닌 악성코드가 디스코드로만 보내는것이며 그것도 순간적인 대다가 netstaus 등으로는 색출해낼수없습니다.

2.하지만 단점도 있습니다.
양방향 통신이아닌 일방적인 통신이기때문에 공격자가 악성코드에 어떠한 명령을 보내는것이 불가능합니다.
지정된 행동만이 실행되며 그이상은 기대할수 없습니다. 하지만 스크린샷 또는 계정탈취(keylogger 혹은 Chromepass*) 캠 등을 가져오게하여서 거의 모든기능은 수행가능합니다.

3.퍼트리기 좋음
이런 종류의 악성코드는 아직 백신등등에서는 검출해내지 못합니다. 에초애 TCP통신이 아니기 때문에 컴퓨터의 통신목록 등으로도 검출이 불가능합니다.
그리고 추후 추가될예정(아직 모름)이지만 피해자가 어떤 파일을 공유할때 그 파일의 대표적인 실행파일을 악성코드와 자동으로 결합시킬수도있습니다.
그리고 이것도 추후 추가될예정이자만 서로다른 버전(혹은 서로다른 웹훅링크)의 악성코드가 발견될경우 먼저있던 악성코드를 자신의 버전으로 업그레이드 시키는 기술도 구현할것입니다.

chromepass* : 현재 chromepass가 막혀서 기다려봐야할거 같습니다.
