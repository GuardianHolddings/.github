## Code Convention
- https://google.github.io/styleguide/tsguide.html

## Git Branch Strategy
### Github Flow를 사용하며, 다음의 절차로 브랜치를 생성한다.

1. 브랜치는 반드시 Github에서 생성된 Issue 상세페이지에서 생성한다.
2. 브랜치를 생성할 때에는 다음의 룰을 따른다.
  1. 브랜치명 규칙: **{{ PROJECT_NAME }}/#{{ 이슈번호 }}**
  2. Github remote에도 브랜치가 생성되도록 "Open branch with GitHub Desktop"를 선택한다.

### PROJECT_NAME은 workspace.json에 정의된 이름을 사용하되 "feature"는 제거한다.
<pre>
"projects": {
    "api-feature-account": "apps/api/feature-account",
    "api-feature-wallet": "apps/api/feature-wallet",
    "api-main": "apps/api/main",
    
    "cdef-web-feature-account": "apps/cdef-web/feature-account",
    "cdef-web-feature-wallet": "apps/cdef-web/feature-wallet",
    "cdef-web-main": "apps/cdef-web/main",
    
    "shared": "libs/shared",
    "shared-api": "libs/shared-api",
    "shared-cdef-web": "libs/shared-cdef-web"
  }
</pre>

### 브랜치명 예시
#### cdef-web
- cdef-web-account/#1
- cdef-web-account/#2
#### api
- api-account/#3
- api-wallet/#4

<img width="469" alt="image" src="https://user-images.githubusercontent.com/18748215/183349220-b39535a0-4183-43fe-89ea-9ddc6979a5d6.png">

