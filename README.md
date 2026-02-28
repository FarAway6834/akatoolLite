# akatool
학원 공부용 툴

*`pip install akatoollite`*

## warning

1. it use __builtin__ scope. (incognito chrome opener in windows, because of that env is win)
2. __main__ also open a [codeup.kr] and then open python shell
3. `akatool.confapp <conf.csv path>` open all link in `<conf.csv path>` then run __main__

## 참고사항

ㅂㅅ같은 의존성을가진 edprompt페키지 사용하여서 프로그래밍하는 툴킷이었음, 그냥 설치 하나로 뚜따하는 ㅂㅅ같은짓을 했었음.

그러나, 작성자의 학업 방황이 끝나고 나서, 그런 잣거리가 이상해보였기때문에, 걍 edprompt의존성에서 쓰이지도 않는 owopkg를 없에서 정상화함.

akatoollite에서는 쓰이지도 않는 ipitin의존성을 지움

그렇게 akatoolLite라는 버전으로 바꿨고, 기존 akatool은 akatoolLite를 불러오는식으로 바꿀 생각임.

또한, `http://c.x3.kro.kr`도메인이 만료되면서, 의미없는 url을 수정함.
