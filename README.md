# 🧴 화해 모티브 화장품 사이트 (Final Project)

> **고객 중심 화장품 커뮤니티 & 쇼핑 서비스**  
> “화해”를 벤치마킹한 UI/UX 기반의 웹 사이트 프로젝트입니다.  

---

## 👩‍💻 팀 소개 및 담당 기능

- **팀명**: “화”
- **참여 인원**: 5명  
- **개발 기간**: 2025.08.06 ~ 2025.09.22

### 🧑‍💻 담당자: 이기정
- 게시판 (공지사항 / 문의사항 / 이벤트)
- 대댓글 기능
- 검색 및 필터 기능
- 문의 답변 및 관리자 응대 기능
- UI 디자인 및 프론트엔드 페이지 설계
- Toast UI Editor 적용

---

## 🎯 1. 기획 의도

화장품 시장은 제품이 다양해지면서 **소비자의 후기, 평점, 문의**가 구매 결정에 큰 영향을 미치고 있습니다.  
하지만 여러 브랜드 사이트는 고객 문의나 후기가 분산되어 있어 접근성이 낮습니다.  

이에 따라 **“화해” 앱을 모티브**로 삼아,  
고객이 손쉽게 화장품 정보를 탐색하고,  
소통할 수 있는 **고객 중심 웹 플랫폼**을 구현했습니다.

---

## 📝 2. 프로젝트 목적

- 고객 문의, 후기, 이벤트 등 **고객 응대 중심 서비스 제공**
- 직관적이고 **사용자 친화적인 UI/UX 디자인**
- **게시판 기반의 안정적 CRUD 구조**
- 관리자 페이지를 통한 **운영 효율성 강화**

---

## 💄 3. 프로젝트 소개

- 화장품 정보, 랭킹, 커뮤니티 등 다양한 뷰티 콘텐츠 제공  
- 회원은 게시판을 통해 의견 공유 및 문의 가능  
- 관리자 페이지에서 문의 답변 및 이벤트 관리  
- **Toast UI Editor**로 풍부한 게시물 작성 경험 제공  

---

## 🔍 4. 벤치마킹

| 벤치마킹 대상 | 주요 참고 요소 |
|----------------|----------------|
| **화해(화장품 리뷰 앱)** | 직관적 UI, 제품 후기 중심 구조 |
| **올리브영몰** | 상품 카테고리 및 검색 필터 구조 |
| **인스타그램** | 사용자 간 소통 구조, 디자인 톤 |

---

## 🛠️ 5. 기술 스택

| 구분 | 기술 |
|------|------|
| **Backend** | Spring Boot, MyBatis |
| **Frontend** | Thymeleaf, HTML, CSS, JavaScript |
| **Database** | Oracle 18c |
| **Tools** | IntelliJ, Eclipse, GitHub |
| **기타** | Toast UI Editor, Chart.js, jQuery |

---

## 🧩 6. ERD

<img width="4520" height="2611" alt="ERD" src="https://github.com/user-attachments/assets/911caaa6-0c01-411b-9315-2f90906c4e69" />

---

## ✨ 7. 주요 기능

| 기능 구분 | 상세 설명 |
|------------|------------|
| **게시판 관리** | 공지사항, 문의사항, 이벤트 게시판 구현 (CRUD) |
| **대댓글 기능** | 댓글과 대댓글로 사용자 간 소통 강화 |
| **검색 및 필터** | 키워드, 카테고리별 게시물 검색 |
| **관리자 페이지** | 문의 응답, 공지 등록, 회원 관리 |
| **에디터 적용** | Toast UI Editor로 풍부한 게시물 작성 지원 |
| **랭킹 기능** | 인기 제품 순위 표시 |
| **UI 디자인** | 직접 기획 및 설계한 반응형 메인 페이지 |

---

## 💬 8. 트러블슈팅

| 문제 상황 | 해결 방법 |
|------------|------------|
| **댓글 삭제 시 대댓글이 함께 삭제되지 않음** | SQL의 `ON DELETE CASCADE` 설정 및 서비스 단에서 부모-자식 관계 로직 수정 |
| **Toast UI Editor 이미지 업로드 실패** | 이미지 Base64 인코딩 후 서버단에서 파일로 변환 저장하도록 로직 수정 |
| **게시판 검색 시 페이징 오류** | `MyBatis`의 동적 쿼리 및 `LIMIT` 처리 로직 수정으로 정상 작동 |
| **관리자 페이지 UI 불일치** | CSS 모듈화 및 공통 템플릿 적용으로 일관성 확보 |

---

## 📷 9. 구현 화면

### 게시판 (공지사항)
<img width="1374" height="693" alt="image" src="https://github.com/user-attachments/assets/34d460bc-90ba-4eab-a3ad-e920c83fd5e9" />

### 랭킹
<img width="1405" height="799" alt="image" src="https://github.com/user-attachments/assets/cf1f117b-f6d8-4598-98b5-275ad604c96d" />

### 커뮤니티
<img width="1373" height="747" alt="image" src="https://github.com/user-attachments/assets/b23789e5-24a1-4fb1-bafe-005fec14577a" />

### 문의사항
<img width="1393" height="772" alt="image" src="https://github.com/user-attachments/assets/5de04548-3133-4962-a499-819dd5b85e87" />
<img width="1429" height="646" alt="image" src="https://github.com/user-attachments/assets/527ffb61-abce-41b8-ba42-f6763bb16eb7" />

### 관리자 게시판
<img width="1428" height="809" alt="image" src="https://github.com/user-attachments/assets/7420284e-d99d-4c6f-bd1c-d0235d522c56" />

### 다이어그램
<img width="1382" height="929" alt="결제" src="https://github.com/user-attachments/assets/11f979b3-f963-4082-a8b6-861421448f6e" />

---

## 🧠 10. 핵심 코드 예시

### 🔹 게시판 작성 (Controller)
```java
@PostMapping("/notice/write")
public String writeNotice(NoticeDTO noticeDTO, RedirectAttributes redirectAttributes) {
    noticeService.insertNotice(noticeDTO);
    redirectAttributes.addFlashAttribute("message", "공지사항이 등록되었습니다.");
    return "redirect:/notice/list";
}
### 🔹 대댓글 등록 (Service)
@Override
public void insertReply(ReplyDTO replyDTO) {
    if(replyDTO.getParentId() != null) {
        replyMapper.insertChildReply(replyDTO);
    } else {
        replyMapper.insertParentReply(replyDTO);
    }
}
### 🔹 게시판 검색 (Mapper XML)
<select id="searchNotice" parameterType="map" resultType="NoticeDTO">
    SELECT * FROM notice
    WHERE title LIKE '%' || #{keyword} || '%'
    OR content LIKE '%' || #{keyword} || '%'
    ORDER BY created_date DESC
</select>

