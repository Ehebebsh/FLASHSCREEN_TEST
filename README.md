# 🚀 스플래쉬 화면 (Splash Screen)

플러터(Flutter)에서 **스플래쉬 화면**은 애플리케이션이 실행될 때 사용자가 첫 번째로 보게 되는 화면이다. 일반적으로 앱이 초기화되거나 로딩되는 동안 앱의 로고나 브랜드를 보여주고, 초기 데이터를 로드하거나 리소스를 준비하는 동안 사용자를 기다리게 하는 데 사용된다.

## 🛠️ 1. 실행 과정

### 1.1 패키지 설치
<details>
<summary>flutter_native_splash 패키지 설치</summary>
<div markdown="1">

스플래쉬 화면을 쉽게 구현하기 위해 **flutter_native_splash** 패키지를 사용한다. 패키지 설치는 아래 링크를 통해 가능하다:

- **패키지 링크**: [flutter_native_splash](https://pub.dev/packages/flutter_native_splash)

```yaml
dependencies:
  flutter_native_splash: ^2.0.5
```

</div>
</details>

### 1.2 flutter_native_splash.yaml 파일 생성
<details>
<summary>설정 파일 생성 및 커스터마이징</summary>
<div markdown="1">
공식 문서의 README를 참고하여 flutter_native_splash.yaml 파일을 생성한다. 이 파일에서 스플래쉬 화면에 표시할 로고와 배경색을 설정할 수 있다.

```yaml
flutter_native_splash:
  color: "#ffffff"
  image: assets/images/splash_logo.png
  android: true
  ios: true
```

원하는 로고와 배경색을 설정하여 커스터마이징한다.
</div>
</details>

### 1.3 명령어 실행
<details>
<summary>스플래쉬 화면 생성 명령어 실행</summary>
<div markdown="1">
설정이 완료되면, 아래 명령어를 터미널에 입력하여 스플래쉬 화면을 생성한다:

```bash
flutter pub run flutter_native_splash:create
```
이 명령어를 실행하면 스플래쉬 화면 설정이 자동으로 적용된다.
</div>
</details>

# 🎥 2. 실행 화면
아래는 앱이 실행될 때 나타나는 스플래쉬 화면의 예시이다. 로고와 배경색이 설정된 모습을 확인할 수 있다.

<p align="center">
  <img src="https://github.com/user-attachments/assets/74b3792a-f4ed-4e06-828e-1f54a6f7509f" alt="Splash Screen Demo" width="300">
</p>
