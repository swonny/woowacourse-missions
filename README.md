# ✍🏻 우아한테크코스 기록

## 레벨 1

|미션|레포지토리|1단계 PR|2단계 PR|관련 포스팅|
|:---:|:----:|:----:|:----:|:----:|
|자동차 경주 게임|[java-racingcar](https://github.com/swonny/java-racingcar)|[1단계 PR](https://github.com/woowacourse/java-racingcar/pull/471)|[2단계 PR](https://github.com/woowacourse/java-racingcar/pull/614)|-|
|사다리 타기|[java-ladder](https://github.com/swonny/java-ladder)|[1단계 PR](https://github.com/woowacourse/java-ladder/pull/114)|[2단계 PR](https://github.com/woowacourse/java-ladder/pull/240)|-|
|블랙잭|[java-blackjack](https://github.com/swonny/java-blackjack)|[1단계 PR](https://github.com/woowacourse/java-blackjack/pull/418)|[2단계 PR](https://github.com/woowacourse/java-blackjack/pull/562)|-|
|체스|[java-chess](https://github.com/swonny/java-chess)|[1단계 PR](https://github.com/woowacourse/java-chess/pull/487)|[2단계 PR](https://github.com/woowacourse/java-chess/pull/624)|-|
</br>

## 레벨 2

|미션|레포지토리|1단계 PR|2단계 PR|관련 포스팅|
|:---:|:----:|:----:|:----:|:----:|
|자동차 경주 게임|[jwp-racingcar](https://github.com/swonny/jwp-racingcar)|[1단계 PR](https://github.com/woowacourse/jwp-racingcar/pull/98)|[2단계 PR](https://github.com/woowacourse/jwp-racingcar/pull/154)|-|
|장바구니|[jwp-shopping-cart](https://github.com/swonny/jwp-shopping-cart)|[1단계 PR](https://github.com/woowacourse/jwp-shopping-cart/pull/250)|[2단계 PR](https://github.com/woowacourse/jwp-shopping-cart/pull/313)|-|
|지하철 노선도|[jwp-subway-path](https://github.com/swonny/jwp-subway-path)|[1단계 PR](https://github.com/woowacourse/jwp-subway-path/pull/31)|[2단계 PR](https://github.com/woowacourse/jwp-subway-path/pull/192)|-|
|쇼핑 주문|[jwp-shopping-order](https://github.com/swonny/jwp-shopping-order)|배포|[2단계 PR](https://github.com/woowacourse/jwp-shopping-order/pull/79)|-|
</br>

## 레벨 3

### 팀 프로젝트

- [레포지토리](https://github.com/woowacourse-teams/2023-3-ddang)
- [안드로이드 앱 다운로드](https://play.google.com/store/apps/details?id=com.ddangddangddang.android&pcampaignid=web_share)
- [서비스 소개](https://sites.google.com/woowahan.com/woowacourse-demo-5th/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8/%EB%95%85%EB%95%85%EB%95%85)

### 데모데이 발표

- [3차 데모데이 발표](https://drive.google.com/file/d/1HiyaF2VQQ3jOFtgkwTlurBXpBv-V4z5a/view)

### 프로젝트 구조 개선 논의

|논의 사항|관련 링크|설명|작업 PR|
|:-------|:-----:|:----|:----------:|
|기술 스택 선정 이유|[링크](https://github.com/woowacourse-teams/2023-3-ddang/wiki/%EB%B0%B1%EC%97%94%EB%93%9C-%EA%B8%B0%EC%88%A0-%EC%8A%A4%ED%83%9D-%EB%B0%8F-%EC%82%AC%EC%9A%A9-%EC%9D%B4%EC%9C%A0)|Java 17과 SpringBoot 3점대 사용 이유|-|
|인프라 구조 개선|[링크](https://github.com/woowacourse/infra-architecture-4/discussions/5#discussioncomment-6986970)|SPOF를 예방하기 위해 인프라 구조 개선 방법 논의|
|700여 개의 테스트 코드 리팩터링|[회의록 링크](https://tasteful-fork-3a7.notion.site/eb002e3665764e388dca2ff00e111eed?pvs=4)|테스트 given절이 지나치게 길어져 리뷰에 어려움이 생겨 모든 테스트에 픽스처를 도입하는 리팩터링 진행|[PR](https://github.com/woowacourse-teams/2023-3-ddang/pull/486)|
|추상화를 통한 JPA 의존성 개선|[개선 방향 회의록 링크](https://tasteful-fork-3a7.notion.site/902649aaefd64d80bf0a7f15c5e72e3e?pvs=4)|서비스에서 JPA 레포지토를 의존하고 있어 특정 기술에 의존적인 구조를 개선하고자 레포지토리를 추상화하는 리팩터링 진행|[PR 1](https://github.com/woowacourse-teams/2023-3-ddang/pull/694)</br>[PR 2](https://github.com/woowacourse-teams/2023-3-ddang/pull/696)|

</br>

## 레벨 4

|미션|레포지토리|PR (1단계 ~ 4단계)|
|:---:|:----:|:----|
|톰캣 구현하기|[jwp-dashboard-tomcat](https://github.com/swonny/jwp-dashboard-http)|[1단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/385)</br>[2, 3단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/412)</br>[4단계 PR](https://github.com/woowacourse/jwp-dashboard-http/pull/476)|
|@MVC 구현하기|[jwp-dashbaord-mvc](https://github.com/swonny/jwp-dashboard-mvc)|[1단계 PR](https://github.com/woowacourse/jwp-dashboard-mvc/pull/432)</br>[2단계 PR](https://github.com/woowacourse/jwp-dashboard-mvc/pull/518)</br>[3단계 PR](https://github.com/woowacourse/jwp-dashboard-mvc/pull/568)|
|JDBC 라이브러리 구현|[jwp-dashboard-jdbc](https://github.com/swonny/jwp-dashboard-jdbc)|[1, 2단계 PR](https://github.com/woowacourse/jwp-dashboard-jdbc/pull/410)</br>[3단계 PR](https://github.com/woowacourse/jwp-dashboard-jdbc/pull/534)</br>[4단계 PR](https://github.com/woowacourse/jwp-dashboard-jdbc/pull/584)|
|레거시 코드 리팩터링|[jwp-refactoring](https://github.com/swonny/jwp-refactoring)|[1단계 PR](https://github.com/woowacourse/jwp-refactoring/pull/486)|[2단계 PR]</br>(https://github.com/woowacourse/jwp-refactoring/pull/668)|
</br>
