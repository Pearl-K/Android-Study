# Android RoadMap Study

## Members

| ![img1](https://avatars.githubusercontent.com/u/Pearl-K) | ![img2](https://avatars.githubusercontent.com/u/SuHyeon00) | 
|--------|--------|
| [강진주](https://github.com/Pearl-K) | [오수현](https://github.com/SuHyeon00) |

## Contents

1. **Android 시스템**
    - Linux 위에 올려진 오픈소스로 시작한 안드로이드
    - 커널 수준의 지식이 필요한 이유 (가볍게 다루기)
        - 시스템 수준의 최적화가 필요할 때
        - 배터리나 디바이스 성능 개선에 필요
    - Android의 커널의 특징
        - Android 커널만 가지는 추가 기능
        - 모바일을 위한 최적화, 저전력, 경량화
    
    → 이 외, 필요한 OS 지식 수준이 스터디원별로 다르기 때문에 개별 학습 추천
    
2. **Kotlin**
    - Java와 비교했을 때 공통점과 차이점
    - 안드로이드 개발 트렌드가 Java → Kotlin으로 변한 이유
    - DalvikVM(JIT) 에서 ART 로의 변화
    - 어노테이션 시스템 비교 (Java 기반의 Kapt → Kotlin 자체 시스템인 KSP)
    - Kotlin 문법 특징과 장점 (람다 함수, null check 등)
    - Kotlin Test Code (Kotest, JUnit5)
3. **Android APP 설계**
    - 싱글 모듈과 멀티 모듈 설계
    - MVVM과 MVI (나머지 디자인 패턴은 가볍게 리마인드)
    - Clean Architectures (실습 코드까지)
4. **Android APP UI**
    - XML
    - Jetpack Compose
        - State와 Recomposition
    - 각각의 장단점 정리 & 비교
5. **Android 생명 주기**
    - Activity 생명 주기
    - Composable 생명 주기
6. **Android APP 내 동시성 처리**
    - APP 내부에서 동시성 처리가 중요한 부분 체크
    - RxJava (스트림 기반)
    - Coroutine (스레드보다 작은 단위의 독자적인 동시성 처리 단위)
    - RxJava와 Coroutine의 비교
        - 어떤 상황에서 사용하는지
        - (서비스 기업에서) RxJava를 사용하는 기업과 Coroutine으로 전환된 기업의 특징, 서비스 분석
7. **Android APP 내 HTTP 통신 처리**
    - Retrofit2 (okhttp, httpclient 뜯어보기)
    - Request, Response 처리할 때 바람직한 방법? (+ Retrofit client 다루는 법)
8. **WearOS**
    - WearOS Powered By SAMSUNG
