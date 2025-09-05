
# 스트리밍 앱 : Laviu
<img width="1920" height="1080" alt="포폴용 헤더-나히라뷰" src="https://github.com/user-attachments/assets/384c2137-72b5-4f93-8294-a5ce52ad2b20" />

- 자바와 스프링부트를 활용하여 Rest API 서버를 제작하였습니다.
- 전체 개발 기간 : 2025.08.04 ~ 2025.08.26


  <br>
## 프로젝트 소개
<div style="display: flex; gap: 10px;">
  <img src="https://nimage.g-enews.com/phpwas/restmb_allidxmake.php?idx=5&simg=2023121004092903370c5fa75ef8612254575.jpg" width="150">
  <img src="https://play-lh.googleusercontent.com/p9zXgkP4pkCDVR-dQ2HfcHyD5vg9MTjDLFVpckObdHI9dGiiMO9TldFJ7kc5bgEGwYjo" width="150">
</div>

- 이 프로젝트는 치지직과 숲 앱을 벤치마킹하여 개발한 실시간 스트리밍 플랫폼으로, 방송 송출·시청, 팔로우, 알림 등 핵심 기능을 직접 구현하며 서비스 아키텍처와 사용자 경험을 설계한  프로젝트입니다.

  <br>
  
## 시연영상


<p align="center">
  이미지 클릭시 영상으로 이동 👇 <br><br>
  <a href="https://youtu.be/_fMoaeDEEHw">
    <img src="https://img.youtube.com/vi/_fMoaeDEEHw/0.jpg" alt="Laviu 시연 영상">
  </a>
</p>

## ⚙️ 기술 스택

### 🛠️ 사용 기술

<table>
  <tr>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="50"/><br/>
      Java
    </td>
    <td align="center">
      <img src="https://cdn.simpleicons.org/springboot/6DB33F" width="50"/><br/>
      Spring Boot
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="50"/><br/>
      RestDoc
    </td>
    <td align="center">
      <img src="https://cdn.simpleicons.org/hibernate/59666C" width="50"/><br/>
      JPA(Hibernate)
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" width="50"/><br/>
      H2
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">
      <img src="https://cdn.simpleicons.org/naver/03C75A" width="50"/><br/>
      Naver OAuth 2.0
    </td>
    <td align="center">
      <img src="https://cdn.simpleicons.org/spring/6DB33F" width="50"/><br/>
      Spring WebSocket (STOMP)
    </td>
    <td align="center">
      <img src="https://cdn.simpleicons.org/springsecurity/6DB33F" width="50"/><br/>
      Spring Security
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" width="50"/><br/>
      Nginx-RTMP
    </td>
    <td align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="50"/><br/>
      Docker
    </td>
  </tr>
</table>

### 🧰 개발 환경

<table>
    <tr>
        <td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="50"/><br/>IntelliJ</td>
    </tr>
</table>

### 🤝 협업 도구

<table>
    <tr>
        <td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="50"/><br/>Git</td>
        <td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="50"/><br/>GitHub</td>
        <td align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Notion_app_logo.png" width="50"/><br/>Notion</td>
        <td align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/7/76/Slack_Icon.png" width="50"/><br/>Slack</td>
    </tr>
</table>

<br>


## 주요 기능

### 공통

- 로그인, 회원가입
- 유효성 검사
- 인증 체크
- Rest Doc 문서

### 방송

- 방송 목록, 등록, 수정
- 방송 해시태그 등록, 수정
- 방송 신고
    - 특정 사유로 방송을 신고함
- 방송 송출, 수신
    - nginx-rtmp 서버로 구현
    - docker 사용함

### 채팅

- 웹소켓을 사용한 실시간 채팅
- 채팅 목록, 등록
- 채팅 참가자 목록
- 채팅 제재
    - 채팅금지
    - 강제퇴장

### 팔로잉

- 팔로잉 목록, 등록, 삭제
- 팔로잉 유저 목록
- 팔로잉 유저의 방송 목록

### 검색

- 유저 검색
- 방송 검색
    - 해시태그를 기준으로 검색

### 유저 페이지

- 유저의 상세 정보 확인
- 유저의 닉네임, 자기소개 변경 가능

### 관리자 페이지

- 신고 목록
    - 신고 수락 및 거절
- 유저 목록
- 방송 목록
    - 방송 강제 종료

<br>

## 담당 업무

<ul>
 <li>방송 등록 및 방송 상세 페이지 기능 구현</li>
  <li>팔로잉 등록 및 삭제 기능 개발</li> 
  <li>유저 검색 및 라이브 방송 검색 기능 구현</li> 
  <li>방송 신고 등록 기능 추가</li> 
  <li>알림 등록 및 알림 목록 조회 기능 구현</li>
  <li>Rest Docs 기반 API 문서 자동화</li> 
</ul>

<br>



## 트러블슈팅
### 1. 사례 – 검색 기능에서 공백/NULL 입력 시 예외 처리 문제

**문제**  
- 검색창에 공백(" ")이나 NULL 값이 입력될 경우, 전체 리스트가 반환되거나 예외 발생  
- 기획 의도는 “검색 조건이 없으면 아무것도 보이지 않게 처리”하는 것  

**해결**  
- Repository 계층에서 검색어의 공백을 제거하고 `trim()` 처리 후 NULL → `""` 로 변환  
- JPQL 쿼리에서 `<> ''` 조건을 추가하여, 검색어가 비어 있을 경우 결과를 반환하지 않도록 처리  

```java
public List<Streams> findAllByQuery(String query) {

    // 공백 제거 , 빈 문자열 처리
    String queryResult = (query == null) ? "" : query.replaceAll(" ", "").trim();

    // 검색 쿼리
    String jpql = """
            select distinct s
            from Streams s
            join  s.streamHashtagList sh
            join  sh.hashtag h
            where s.status = :live
            and (:query <> '' and lower(h.name) like concat('%', lower(:query), '%'))
            """;

    return em.createQuery(jpql, Streams.class)
            .setParameter("query", queryResult)
            .setParameter("live", StreamsStatus.LIVE)
            .getResultList();
}
```

---

### 2. 사례 – 팔로잉 등록/삭제 시 중복 및 무결성 문제

**문제**  
- 팔로잉 등록 시 동일한 유저를 여러 번 팔로우할 수 있어 중복 데이터 발생  
- 팔로잉 삭제 후 즉시 목록을 조회할 때 캐시/지연로딩 문제로 삭제가 반영되지 않는 현상 발생  

**해결**  
- DB 테이블에 `(follower_id, following_id)`에 대해 Unique 제약 조건 추가  
- JPA `save()` 호출 전 중복 여부를 검사  
- 삭제 후에는 즉시 `flush()` 처리하여 목록 조회 시 최신 상태를 보장  

```java
// Repository 예시
public interface FollowRepository extends JpaRepository<Follow, Long> {
    boolean existsByFollowerIdAndFollowingId(Long followerId, Long followingId);
    void deleteByFollowerIdAndFollowingId(Long followerId, Long followingId);
}

// Service 예시
@Transactional
public void follow(Long followerId, Long followingId) {
    if (followRepository.existsByFollowerIdAndFollowingId(followerId, followingId)) {
        throw new IllegalStateException("이미 팔로잉한 유저입니다.");
    }
    followRepository.save(new Follow(followerId, followingId));
}

@Transactional
public void unfollow(Long followerId, Long followingId) {
    followRepository.deleteByFollowerIdAndFollowingId(followerId, followingId);
    entityManager.flush(); // 즉시 반영
}
```

---

### 3. 사례 – 방송 시작 시 스트림 키(UUID) 생성 및 관리 문제

**문제**  
- 방송 스트림 키는 사용자별로 **한 번만 생성되어 DB에 저장**되어야 하는데,  
  - 중복 요청이나 동시성 문제로 인해 동일 유저에게 여러 개의 키가 발급되는 사례 발생  
  - 키가 중복되면 OBS 인증 실패, 방송 접속 오류 등 예기치 못한 문제가 생김  

**해결**  
- 키 생성 전 반드시 DB에서 해당 유저의 기존 키 존재 여부를 확인  
- 이미 존재하면 기존 키를 반환하고, 없을 경우에만 `UUID`를 새로 발급  
- `user_id` 컬럼에 `UNIQUE` 제약 조건을 추가하여 중복 저장 방지  

```java
// Service 예시
@Transactional
public String generateStreamKey(Long userId) {
    return streamKeyRepository.findByUserId(userId)
            .map(StreamKey::getKey) // 기존 키가 있으면 그대로 반환
            .orElseGet(() -> {
                String newKey = UUID.randomUUID().toString();
                streamKeyRepository.save(new StreamKey(userId, newKey));
                return newKey;
            });
}
```


<br>

## 화면 와이어프레임
[화면 설계 라뷰 (와이어프레임).pdf](https://github.com/user-attachments/files/22168602/default.pdf)


  <br>
  
## ERD

![erd](docs/images/erd.png)

```
