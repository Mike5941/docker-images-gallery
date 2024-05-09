# Docker Project

**도커파일** 및 **도커 컴포즈** 섹션용 프로젝트

## 초기 구성

- https://unsplash.com 에서 계정을 만듭니다.
- https://unsplash.com/oauth/applications 에서 **"이미지 갤러리"**라는 제목으로 **데모** 애플리케이션을 새로 생성합니다.
데모 애플리케이션은 시간당 50건의 요청으로 제한됩니다.
- 새로 생성한 애플리케이션에서 **"키"** 섹션을 찾아 **액세스 키**를 복사합니다.
- API** 폴더에 **.env.local** 파일을 생성하고 다음 줄을 추가합니다:

```
UNSPLASH_KEY=<Paste copied Access Key here>
```

가짜 코드가 포함된 **예시**(앱에서 사용하지 마세요):

```
UNSPLASH_KEY=2MJvApIkV13hfg2LmQlneILfHoJ2ttlzSdPKefGOyKM
```

- 수정된 **.env.local** 파일 저장
