---
layout: single
title: "FlutterInstall"


---

＃FlutterInstall

플러터 개발을 위한 설치방법에 대해서 기록해 보았습니다.

1.https://docs.flutter.dev/get-started/install

플러터 공식 홈페이지에 접속해서 자신의 운영체제에 맞는 SDK를 설치해줍니다

![image-20230606230115361](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230115361.png)

다운로드를 하고 압축을 풀어줍니다.

![image-20230606230218457](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230218457.png)

2.안드로이드 스튜디오로 이동해 Plugins에서 Flutter를 Install해줍니다.

![image-20230606230323041](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230323041.png)

![image-20230606230358105](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230358105.png)

3.다음으로 MoreAction -> SDK매니저를 눌러 Android SDK Command-line Tools를 Install해줍니다.

![image-20230606230442086](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230442086.png)

![image-20230606230520610](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230520610.png)

![image-20230606230528093](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230528093.png)

4. 이제 환경변수를 설정해야합니다 내PC -> 마우스 오른쪽 클릭 -> 속성 -> 고급시스템 설정 -> 환경변수순으로 진행합니다.

   ![image-20230606230738854](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230738854.png)

고급시스템 설정 클릭

![image-20230606230800754](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230800754.png)

![image-20230606230842634](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606230842634.png)

Path를 클릭하고 편집을 클릭!

![image-20230606231015386](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606231015386.png)

새로만들기를 클릭 후 다운받았던 Flutter파일의 bin 주소를 환경변수에 넣어줍니다.

​															 ![image-20230606231513938](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606231513938.png)

![image-20230606231441262](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606231441262.png)

5. 다음으로 CMD창을 열어 flutter doctor를 입력합니다.

![image-20230606232708006](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606232708006.png)

![image-20230606232759886](D:\Project\limkk90.github.io\limkk90.github.io\images\2023-06-06-FlutterInstall\image-20230606232759886.png)

flutter doctor을 입력했더니 Android toolchain 과 Visual Studio 두가지의 Issue가 나왔습니다.

#해결방법

