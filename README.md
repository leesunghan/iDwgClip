# iDwgClip
설계도면의 일부분을 클립하는 유틸리티 프로그램

- 관리자 : arx119@gmail.com
- 생성일 : 2004년 06월 21일
- 수정일 : 2004년 06월 19일 (1.0.0.3)
- 수정일 : 2004년 07월 14일 (1.0.0.4)
- 수정일 : 2013년 12월 21일 (1.0.0.5)
- 수정일 : 2014년 01월 25일 (1.0.0.5)
- 수정일 : 2014년 01월 25일 (1.0.0.8)
- 버  젼 : iDwgClip 1.0.0.8 - beta

>## 프로그램 설명
- iDwgClip 프로그램은 AutoCAD(LT) 2000~2018 (32/64)에서 동작하는 프로그램 입니다.
- 부분상세도를 만들어주는 기능을 추가함 (명령어 : clipcopy)
- 다중 클리핑을 생성해주는 기능을 추가함 (명령어 : mclip)

>## 프로그램 테스트
O.S     : Windows XP/8.1/10
AutoCAD : 2000~2018 (32/64)

>## 사용 방법
명령입력창에서 "clipcopy", "mclip" 을 실행합니다.

![Alt text](/images/image00.gif "mclip")

![Alt text](/images/image01.gif "clipcopy")

>## AutoCAD 버전별 arx 버전
- AutoCAD R2000~2002 (win32) : iDwgClip2000.arx    (mclip 지원하지 않음)
- AutoCAD R2004~2006 (win32) : iDwgClip2004.arx    (mclip 지원하지 않음) 
- AutoCAD R2007~2009 (win32) : iDwgClip2007.arx    (mclip 지원하지 않음) 
- AutoCAD R2007~2009 (x64)   : iDwgClip2007x.arx   (mclip 지원하지 않음)
- AutoCAD R2010~2012 (win32) : iDwgClip2010.arx    (mclip 지원)
- AutoCAD R2010~2012 (x64)   : iDwgClip2010x.arx   (mclip 지원)
- AutoCAD R2013~2014 (win32) : iDwgClip2013.arx    (mclip 지원) 
- AutoCAD R2013~2014 (x64)   : iDwgClip2013x.arx   (mclip 지원)
- AutoCAD R2015~2016 (win32) : iDwgClip2015.arx    (mclip 지원) 
- AutoCAD R2015~2016 (x64)   : iDwgClip2015x.arx   (mclip 지원)
- AutoCAD R2017 (win32)      : iDwgClip2017.arx    (mclip 지원) 
- AutoCAD R2017 (x64)        : iDwgClip2017x.arx   (mclip 지원)
- AutoCAD R2018 (win32)      : iDwgClip2018.arx    (mclip 지원) 
- AutoCAD R2018 (x64)        : iDwgClip2018x.arx   (mclip 지원)

>## 프로그램 로딩방법
iDwgClip 프로그램은 독립적으로 로딩이 가능하므로, 아래와 같은 방법으로
실행할 수 있습니다. 
- appload에서 arx프로그램을 지정합니다.          : Application
- (arxload "iDwgClip2004.arx")                   : Lisp
- acedLoadModule("iDwgClip2004.arx", true)       : ObjectARX

>## 프로그램 배포시 유의사항
상업적인 3rd-party에서 함께 Packing하고자 할때는 arx119@gmail.com으로 
사용을 원하는 제품명을 보내시면 사용허가 및 Packing시 도움이 될만한 정보를 
제공해 드리겠습니다.

>## 프로그램 업데이트 정보
- 1.0.0.8  : MClip 명령추가
- 1.0.0.5  : ClipCopy, DivCC 명령추가
- 1.0.0.4  : 2차프로그램 수정. (xclip+의 rectangle옵션 버그수정, vpclip+ 명령추가)
- 1.0.0.3  : 1차프로그램 수정. (xclip+ 명령추가)
- 1.0.0.2  : 초기 모듈 제작.

>## 기능 추가를 원하시거나 버그사항은 arx119@gmail.com으로 보내주세요.
