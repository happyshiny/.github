# 프로젝트

<div align="center">

</div>

## 📅 **프로젝트 기간**

- 2024.04.17 ~

## 🙇🏻‍♂️ **팀원소개**

<div align="center">
  알아서 바꿔

|                   [유수빈](https://github.com/JudithHopps)                    |                                  [백승헌]()                                   |                                  [조현수]()                                   |
| :---------------------------------------------------------------------------: | :---------------------------------------------------------------------------: | :---------------------------------------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/113181934?v=4" width="300"> | <img src="https://avatars.githubusercontent.com/u/113181934?v=4" width="300"> | <img src="https://avatars.githubusercontent.com/u/113181934?v=4" width="300"> |
|                                      FE                                       |                                      BE                                       |                                      FE                                       |

</div>

## ⚒️ **기능 시연**

<details>
<summary>미정  </summary><br/>
<p>
👉 로그인페이지: 토큰을 받아오고, 계정 정보를 받아오면 헤더 이미지와 마이페이지, 로그인 시 자신이 저장한 픽 마커 호출되는 기능, 로그아웃하면 초기화<br/>
<img width=400 src="https://github.com/Wingle-SMWU/Wingle-Frontend/assets/94962427/e8ab2f05-4bbd-4fd6-a1ae-9311cd55dcbe"><br/>
</p>
<p>
👉 회원가입 및 업로드 후 어드민 페이지에서 확인 가능<br/>
<img width=400 src="https://github.com/Wingle-SMWU/Wingle-Frontend/assets/94962427/662a93a9-b831-4d4e-83ba-8cb165dcedf1"><br/>
</p>
</details>

## 🧑🏻‍💻 개발 관련 기술

### 👩🏻‍🔧 **기술 스택**

#### **Front-end**

<div align=left>
<img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" height="35">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&amp;logo=typeScript&amp;logoColor=white" height="35"> 
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&amp;logo=react&amp;logoColor=black" height="35"> 
<img src="https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white" height="35">
<img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&amp;logo=axios&amp;logoColor=white" height="35">
<img src="https://img.shields.io/badge/styled_components-db7093?style=for-the-badge&amp;logo=styled-components&amp;logoColor=white" height="35">
<img src="https://img.shields.io/badge/recoil-3578EC?style=for-the-badge&amp;logo=recoil&amp;logoColor=white" height="35">
<img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&amp;logo=eslint&amp;logoColor=white" height="35">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white" height="35"> 
</div>

#### **Common**

<div align=left> 
<img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white" height="35">
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white" height="35">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white" height="35">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white" height="35">
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white" height="35">
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white" height="35">
</div>

### [📺 화면 설계서]

### 🚧 아키텍쳐

![Web App Reference Architecture V2 (2)](https://user-images.githubusercontent.com/94962427/215998062-cb0ea846-3f4b-42e7-8373-70002c792061.png)

### 📄 API 명세서

<!-- 승헌아~~ -->
<img width="1440" alt="image" src="https://github.com/Wingle-SMWU/Wingle-Frontend/assets/94962427/7b0041e5-2773-4cbb-844a-731a6ccfa8ef">

### 🌟 코딩 컨벤션

1. **Common**

   - 네이밍 글자 길이 : 20자 이내 (20자 이상은 팀원과 상의)
   - 유형별 네이밍 규칙
     - Default : camelCase
     - Folder, File names : lowerCamelCase
     - Component names : PascalCase
     - Function names : lowerCamelCase, 동사 + 명사 (예: getUserInformation)
     - Constant names : CONSTANT_CASE

2. **React**

   - 함수형 컴포넌트 사용
   - 메모이제이션 권장
   - 이벤트 함수 네이밍 : handle + event / const handleOnClickAlarm = () => { ... }
   - 함수 선언 : 선언식으로 작성하되, 표현식을 사용해야 할 경우(클로저, 콜백함수 등) 화살표 함수 사용

3. **Styled-Components**

   - 해당 컴포넌트 파일에 스타일 정의
   - 네이밍 : S-dot 패턴 사용 (예: `const Wrapper = styled.div``)

4. **Recoil**

   - 무분별한 전역상태 사용 금지 : 다수의 컴포넌트 간에 상태 의존성이 높아질 때만 전역상태로 데이터 관리(일반적인 경우 지역상태로 관리)
   - 네이밍 : StateAtom 추가 / `export const imgModalStateAtom = atom({ ... })`

5. **TypeScript**
   - 네이밍 : PascalCase 사용, I/T prefix 사용 금지
   - Type alias와 interface 사용 (API 데이터 등)

## ✔️ 커밋 규칙

#### 이슈 작성 규칙

기본 형식 : [#이슈번호 -] [commit type]: [commit message]
예시 : #1 - feat: 로그인

#### 코딩 컨벤션

- 1. Common

  - 네이밍 글자 길이 : 20자 이내(20자 이상 팀원과 상의)
  - 유형별 네이밍 규칙
    <aside>
    💡 Default : camelCase
    Folder, File names : lowerCamelCase
    Component Function names : PascalCase
    Function names : lowerCamelCase, verb + noun(ex: getUserInformation)
    Constant names : CONSTANT_CASE

    </aside>

    2. React
       - 메모이제이션 권장
       - 함수 선언 : 화살표 함수로 선언

    - 함수형 컴포넌트 작성시 → `export default function Example() {}`
    - 컴포넌트 내부에 있는 함수 작성 시 → `const Example () ⇒ {}`
      - 이벤트 함수 네이밍 : handle + event / const handleOnClickAlarm = () => { ... }

    3. Styled-Components
       - 해당 컴포넌트 파일에 정의
       - 네이밍(S-dot)
    4. Recoil
       - 무분별한 전역상태 사용 금지 : 다수의 컴포넌트간에 상태 의존성이 높아질때만 전역상태로 데이터 관리(일반적인 경우 지역상태로 관리)
       - 네이밍 : StateAtom 추가 / export const imgModalStateAtom = atom({...})
    5. TypeScript

    - naming : PascalCase 사용, I/T prefix 사용 금지
    - type alias + interface(API Data)
    - 충돌성 오류로 둘 중 하나의 방식만 → type 방식으로 쓰기로 결정
    - interface 로 되어 있는 코드 type 으로 수정해주기
