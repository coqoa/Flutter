# Flutter

#### 0. 설치 및 환경변수 등록 
1. Flutter SDK 다운로드  
	`flutter install` 구글 검색  
-> OS에 맞춰서 다운로드  
-> 압축풀기

2. Android Studio 다운로드  
-> 실행  
->  2-1. plugins 메뉴에서 `flutter` 플러그인 검색 / 설치  
->	2-2. more Actions - SDK Manager - SDK Tools 탭 클릭 - `Android SDK Command Line Tools` 설치   

3. 환경 변수 등록  
- 터미널 이름이 zsh일 경우
	- 터미널 오픈 -> `touch ~/.zshrc` 입력, `open ~/.zshrc` 입력  
- 터미널 이름이 bash일 경우
	- 터미널 오픈 -> `touch ~/.bash_profile` 입력, `open ~/.bash_profile` 입력
- `export PATH = "$PATH:flutter의 bin경로(~~~/bin)"` 작성, 저장, 종료 
4. 기타 설치
-	크롬브라우저 설치
-	터미널 오픈해서 `flutter doctor` 입력  
(m1 맥북 에러나면 터미널, 컴퓨터 종료 후 다시 켜고 터미널에 `softwareupdate --install-rosetta` 입력  

5. Android Studio의 New Flutter Project 눌러서 프로젝트 생성  
	(Flutter SDK Path : 압축 푼 flutter 폴더 경로)  
   -> next  
   -> project name(소문자, 띄어쓰기 언더바), location 설정   
   -> language, platform 설정  
   -> finish  
   -> lib폴더의 `main.dart`에 코드 작성  
 
