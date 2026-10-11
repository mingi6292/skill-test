# android-starter

멀티 모듈 Android 프로젝트 시작 템플릿

## 구성
- build-logic convention plugin
    - `convention.android.application` / `convention.android.application.compose`
    - `convention.android.library` / `convention.android.library.compose`
    - `convention.jvm.library`
- Version Catalog (`gradle/libs.versions.toml`)
- GitHub Actions CI (build / unit test / lint)

## 새 프로젝트 시작
1. **Use this template** 또는 `gh repo create <이름> --template mingi6292/android-starter --public --clone`
2. 아래 문자열을 새 값으로 변경 (Match case)
    - `com.mg.starter` → 새 패키지명
    - `Starter` → 새 앱 이름
3. `app/src/*/java/com/mg/starter` 폴더를 새 패키지 경로로 이동