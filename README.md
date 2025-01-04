# Android Roadmap Study


## Members
| <img src="https://avatars.githubusercontent.com/u/80253713" width = 150> | <img src="https://avatars.githubusercontent.com/u/90602694" width = 150> | 
|--------|--------|
| [강진주](https://github.com/Pearl-K) | [오수현](https://github.com/SuHyeon00) |


## Contents
### 1. **Android 시스템**
- Linux 기반 Android 커널의 이해
- 커널 수준의 지식이 필요한 이유
  - 시스템 수준의 최적화가 필요한 경우
  - 배터리나 디바이스 성능 개선
- Android의 커널의 특징
  - Android 커널만 가지는 추가 기능
  - 모바일을 위한 최적화, 저전력, 경량화 전략
- Android 에서 필요한 OS 지식
  - 메모리 관리 (페이징과 메모리 매핑)
  - 여유 메모리를 확보하기 위한 기술 (기존 Linux 커널의 매커니즘을 어떻게 활용하는지)
 
    
### 2. **Kotlin**
- Java와 비교했을 때 공통점과 차이점
- 안드로이드 개발 트렌드 Java → Kotlin 짚고 넘어가기
- DalvikVM(JIT) 에서 ART 로의 변화
  - Runtime 환경 체크하는 이유: 실제 동작 시 전통적인 JVM 환경 위에서 동작하지 않음을 짚고 넘어가기
  - ART 환경에서 동작하며, 이에 따른 컴파일 환경이나 GC에 차이 있음 (But, JVM의 실행 모델과 호환은 됨)
- 어노테이션 시스템 비교 (Java 기반의 Kapt → Kotlin 자체 시스템인 KSP)
- Kotlin 문법 특징과 장점 (람다 함수, null check 등)
- Kotlin Test Tool (Kotest, JUnit5)

### 3. **Android APP 설계**
- 싱글 모듈과 멀티 모듈 설계
- MVVM과 MVI (나머지 디자인 패턴은 가볍게 리마인드)
- Clean Architectures (코드까지 넓게 보기)

### 4. **Android APP UI**
- XML
- Jetpack Compose
  - State와 Recomposition
- 각각의 장단점 정리 & 비교
- 둘 중 무엇을 선택하는게 더 유리한지
  - 실제 기업 사례 분석을 통해 유리한 경우들 나눠서 정리

### 5. **Android 생명 주기**
- Activity 생명 주기
- Composable 생명 주기

### 6. **Android APP 내 동시성 처리**
- APP 내부에서 동시성 처리가 중요한 부분 체크
- RxJava (스트림 기반)
- Coroutine (스레드보다 작은 단위의 독자적인 동시성 처리 단위)
- RxJava와 Coroutine의 비교
   - 어떤 상황에서 사용하는지
    - (서비스 기업에서) RxJava를 사용하는 기업과 Coroutine으로 기술 전환된 기업의 특징, 서비스 분석

### 7. **Android APP 내 HTTP 통신 처리**
- Retrofit2 (okhttp, httpclient 뜯어보기)
- Request, Response 처리할 때 바람직한 방법?

### 8. 그 외 여러가지 주제들
- WearOS Powered By SAMSUNG
- Ktor (KMP 조사하기)
    
