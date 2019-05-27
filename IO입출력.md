
## I/O 입출력
### 입출력이 무엇인가
* A 프로그램에서 B 프로그램으로 데이터를 주고 받는 경우 입력(Input)과 출력(Output)이 반복적으로 일어난다. 
* 사용자가 프로그램을 통해 키보드/마우스/파일 입력(Input)과 모니터/파일 출력(Output)이 가능하다.
* 즉, 프로그램을 통해 데이터를 주고 받을 경우 입출력이 일어난다고 말할 수 있다.

### 자바(Java) 프로그램에서의 입출력이 무엇인가?
* 위에서 정의한 입출력에서 자바프로그램을 통해 입출력을 하는 경우를 의미한다.
* 자바는 사용자/프로그램 간의 입출력을 하기 위해 다양한 Class를 정의되어있고 이를 이용하여 I/O 입출력이 가능하다.
* 자바에서는 입출력이 가능하게 해주는 통로를 Stream(스트림)으로 정의함.

### 입출력(I/O) 스트림(Stream)
* 입출력으로 데이터를 주고받기 위해서는 Stream을 생성해야 한다.
* Stream은 무조건 단방향이기때문에 데이터를 주고 받기 위해서는 입/출력 Stream을 각각 생성하여 사용하여야 한다.

* 프로그램 데이터 입출력(I/O)
<img src="https://t1.daumcdn.net/cfile/tistory/99D5434A5C1DFAFF0D?download" width="90%"></img>

* 사용자 데이터 입출력(I/O)
<img src="https://t1.daumcdn.net/cfile/tistory/995E91345C1DF8E613?download" width="90%"></img>

## I/O 입출력 종류
### Byte 기반의 처리하는 I/O Stream 종류 및 상속
<img src="http://ccm3.net/wp-content/uploads/2018011801.png" width="90%" height = "50%"></img>
* I/O Stream은 데이터 종류에 따라 class를 적절히 선택하여 사용하여야 한다.
* I/O Stream Class는 InputStreamClass와 OutputStreamClass가 대칭되어 사용된다.
* I/O Stream Class의 최상위 Class는 추상클래스로 구현되어 있으며, InputStream/OutStream이다.
