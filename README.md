## [Effective Java 3/E 스터디]

# 공동 목표

> ### 일정
>
> 25.02.26. ~ 22.04.11 (1구간 팀 스터디 기간)

**자바를 정복하기 위한 스터디 모임**

>- **이펙티브 자바**를 정독하며 효율적인 자바 코드 작성 방법을 익히기
>- 팀원과 함께 스터디를 진행하며 학습 효율 극대화 😊
>- 각자 공부한 내용을 발표하며 깊이 있는 이해와 실력 향상 도모
>- 스터디 기간(1단위) 동안 완독을 목표로!

# 진행 방식

1. 일일 스터디 시간 및 데일리 활동

- 매일 13시 - 16시 (3시간) - 개인 공부

- 매일 16시 - 18시 (2시간) - 팀 스터디(발표 위주)

2. 주차별 활동 및 달성 목표

- 자바 스터디

👉🏻 매주 월요일 책의 원하는 주제를 선택

월, 화, 수 → 서로 모여서 자바 공부

👉🏻 발표는 2조로 나누어서 진행합니다. 팀원을 절반으로 나누어 목요일엔 A조가, 금요일에는 B조가 진행합니다 → 1주일에 챕터 1개씩 발표합니다.

목(A조) 발표자 : 김태환, 윤예진, 지윤식

금(B조) 발표자 : 석진용, 이승욱

- 조 회의로 일자, 시간 변경 지정 예정

3. 월별 활동 및 달성 목표
   **-** 매달 말 코어 회의를 진행해서 그 다음 월별 활동 및 달성 목표 잡기

- 조 회의로 일자,시간 변경 지정 예정

### 업로드 규칙

- 업로드하는 학습자료의 디렉토리는 챕터 - 아이템 번호 - 이름 의 구조로 합니다.
  - ex) 2장 - 아이템_1 - 김태환 - 생성자 대신 정적 팩터리 메서드를 고려하라.md


  - branch 네이밍은 ItemXX_{github계정}의 구조로 합니다.
    - ex) item1_hwan2_99 or item1_mangdi

  - PR(Pull Request) 작성 시 제목은 [아이템XX] : ~~~ (이름)의 구조로 합니다.
    - ex) 아이템1 : 생성자 대신 정적 팩터리 메서드를 고려하라(김태환)

  - commit시 메시지 규칙은 itemXX : (아이템 제목) 의 구조로 합니다.
    - ex) item1 : 생성자 대신 정적 팩터리 메서드를 고려하라



# 이펙티브 자바 목차

- [ ] 1.생성자 대신 정적 팩터리 메서드를 고려하라
- [ ] 2.생성자에 매개변수가 많다면 빌더를 고려하라
- [ ] 3.private 생성자나 열거 타입으로 싱글턴임을 보증하라
- [ ] 4.인스턴스화를 막으려거든 private 생성자를 사용하라
- [ ] 5.자원을 직접 명시하지 말고 의존 객체 주입을 사용하라
- [x] 6.불필요한 객체 생성을 피하라
- [ ] 7.다 쓴 객체 참조를 해제하라
- [ ] 8.finalizer와 cleaner 사용을 피하라
- [ ] 9.try-finally보다는 try-with-resources를 사용하라
- [ ] 10.equals는 일반 규약을 지켜 재정의하라
- [ ] 11.equals를 재정의하려거든 hashCode도 재정의하라
- [ ] 12.toString을 항상 재정의하라]
- [ ] 13.clone 재정의는 주의해서 진행하라
- [ ] 14.Comparable을 구현할지 고려하라
- [ ] 15.클래스와 멤버의 접근 권한을 최소화하라
- [ ] 16.public 클래스에서는 public 필드가 아닌 접근자 메서드를 사용하라
- [ ] 17.변경 가능성을 최소화하라
- [ ] 18.상속보다는 컴포지션을 사용하라
- [ ] 19.상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속을 금지하라.
- [ ] 20.추상 클래스보다는 인터페이스를 우선하라
- [ ] 21.인터페이스는 구현하는 쪽을 생각해 설계하라
- [ ] 22.인터페이스는 타입을 정의하는 용도로만 사용하라
- [ ] 23.태그 달린 클래스보다는 클래스 계층구조를 활용하라
- [ ] 24.멤버 클래스는 되도록 static으로 만들라
- [ ] 25.톱레벨 클래스는 한 파일에 하나만 담으라
- [ ] 26.로 타입은 사용하지 말라]
- [ ] 27.비검사 경고를 제거하라
- [ ] 28.배열보다는 리스트를 사용하라
- [ ] 29.이왕이면 제네릭 타입으로 만들라
- [ ] 30.이왕이면 제네릭 메서드로 만들라
- [ ] 31.한정적 와일드카드를 사용해 API 유연성을 높이라
- [ ] 32.제네릭과 가변인수를 함께 쓸 때는 신중하라
- [ ] 33.타입 안전 이종 컨테이너를 고려하라
- [ ] 34.int 상수 대신 열거 타입을 사용하라
- [ ] 35.ordinal 메서드 대신 인스턴스 필드를 사용하라
- [ ] 36.비트 필드 대신 EnumSet을 사용하라
- [ ] 37.ordinal 인덱싱 대신 EnumMap을 사용하라
- [ ] 38.확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라
- [ ] 39.명명 패턴보다 애너테이션을 사용하라
- [ ] 40.@Override 애너테이션을 일관되게 사용하라
- [ ] 41.정의하려는 것이 타입이라면 마커 인터페이스를 사용하라
- [ ] 42.익명 클래스보다는 람다를 사용하라
- [ ] 43.람다보다는 메서드 참조를 사용하라
- [ ] 44.표준 함수형 인터페이스를 사용하라
- [ ] 45.스트림은 주의해서 사용하라
- [ ] 46.스트림에서는 부작용 없는 함수를 사용하라
- [ ] 47.반환 타입으로는 스트림보다 컬렉션이 낫다
- [ ] 48.스트림 병렬화는 주의해서 적용하라
- [ ] 49.매개변수가 유효한지 검사하라
- [ ] 50.적시에 방어적 복사본을 만들라
- [ ] 51.메서드 시그니처를 신중히 설계하라
- [ ] 52.다중정의는 신중히 사용하라
- [ ] 53.가변인수는 신중히 사용하라
- [ ] 54.null이 아닌, 빈 컬렉션이나 배열을 반환하라
- [x] 55.옵셔널 반환은 신중히 하라
- [ ] 56.공개된 API 요소에는 항상 문서화 주석을 작성하라
- [ ] 57.지역변수의 범위를 최소화하라
- [ ] 58.전통적인 for 문보다는 for-each 문을 사용하라
- [ ] 59.라이브러리를 익히고 사용하라
- [ ] 60.정확한 답이 필요하다면 float와 double은 피하라
- [ ] 61.박싱된 기본 타입보다는 기본 타입을 사용하라
- [ ] 62.다른 타입이 적절하다면 문자열 사용을 피하라
- [ ] 63.문자열 연결은 느리니 주의하라
- [ ] 64.객체는 인터페이스를 사용해 참조하라
- [ ] 65.리플렉션보다는 인터페이스를 사용하라
- [ ] 66.네이티브 메서드는 신중히 사용하라
- [ ] 67.최적화는 신중히 하라
- [ ] 68.일반적으로 통용되는 명명 규칙을 따르라
- [ ] 69.예외는 진짜 예외 상황에만 사용하라
- [ ] 70.복구할 수 있는 상황에는 검사 예외를, 프로그래밍 오류에는 런타임 예외를 사용하라
- [ ] 71.필요 없는 검사 예외 사용은 피하라
- [ ] 72.표준 예외를 사용하라
- [ ] 73.추상화 수준에 맞는 예외를 던지라
- [ ] 74.메서드가 던지는 모든 예외를 문서화하라
- [ ] 75.예외의 상세 메시지에 실패 관련 정보를 담으라
- [ ] 76.가능한 한 실패 원자적으로 만들라
- [ ] 77.예외를 무시하지 말라
- [ ] 78.공유 중인 가변 데이터는 동기화해 사용하라
- [ ] 79.과도한 동기화는 피하라
- [ ] 80.스레드보다는 실행자, 태스크, 스트림을 애용하라
- [ ] 81.wait와 notify보다는 동시성 유틸리티를 애용하라
- [ ] 82.스레드 안전성 수준을 문서화하라
- [ ] 83.지연 초기화는 신중히 사용하라
- [ ] 84.프로그램의 동작을 스레드 스케줄러에 기대지 말라
- [ ] 85.자바 직렬화의 대안을 찾으라
- [ ] 86.Serializable을 구현할지는 신중히 결정하라
- [ ] 87.커스텀 직렬화 형태를 고려해보라
- [ ] 88.readObject 메서드는 방어적으로 작성하라
- [ ] 89.인스턴스 수를 통제해야 한다면 readResolve보다는 열거 타입을 사용하라
- [ ] 90.직렬화된 인스턴스 대신 직렬화 프록시 사용을 검토하라
