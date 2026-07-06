# SGM-KPatch
<img width="939" height="683" alt="image" src="https://github.com/user-attachments/assets/b70c16f9-1b27-4fa4-b2f2-2b2d190d8698" />

PS3 진건담무쌍 한국어 패치

본 패치는 비영리 목적으로 제작되었습니다  

본 패치의 상업적 이용은 금지합니다


본패치를 변조,개조,재배포 하지 마십시오  

본 패치를 공유하거나 롬에 입혀 공유하지 마십시오

저작권으로 인한 법적인 책임은 패치를 사용한 사용자에게  

있음을 알려드립니다

문제 발생시 배포가 중단될 수 있고 추후 작업 또한 중단될 수 있습니다

[게임정보]
기종 : PS3, 일본어
게임명:  真 ガンダム無双
영어명 : Shin Gundam Musou
게임ID : BLJM61140

게임버전: v1.02

 
압축비번:
2013년12월19일_v260629

[준비물]
1. 한글패치 다운로드
2.실행 가능한 원본게임롬(폴더형태)

   파일에 개별 패치해야 하므로
   
   "HDD에서 실행가능한 폴더 형태의 게임폴더"가 필요합니다
   
   원본의 실행 여부를 확인하고 패치를 진행해주세요

   파일 개별 패치이므로 반드시 폴더형태이어야만 합니다.

3. 1.02 EBOOT.BIN 생성 및 복사
 
업데이트 버전1.02에 패치해야하므로 일단 실행후 1.02 업데이트후에

EBOOT.BIN을 가져와야 패치 할 수 있습니다  

다음과 같은 순서로 에뮬을 실행후 EBOOT.BIN을 복사하세요.  


 a. rpcs3에뮬실행  
 
   원본게임폴더를 지정하고 실행.  
   
 b. install하라고 하면 하고 계속 실행  
 
 c. 타이틀 화면 나오면 게임 창을 종료합니다  
 
 d. 1.02 업데이트 설치   
 
    rpcs3에뮬 메뉴에서 install pakages/rap./edat... 메뉴를 누르고 1.02update pkg를 설치.  
    
    설치가 끝나면 1.02라고 표시되어 있는지 확인합니다.  
    
    1.02라고 되어 있으면 에뮬을 종료합니다.   
    
   간혹 프로세스에 떠 있는경우도 있으니 "작업관리자"띄워서 rpcs3.exe있나 확인, 없으면 OK  
   

 e. rpcs3 설치폴더/dev_hdd0/game/BLJM61140_INSTALL 폴더를 삭제합니다 (반드시 삭제해야 합니다)  
 
 f. rpcs3 설치폴더/dev_hdd0/game/BLJM61140/USRDIR/EBOOT.BIN  
 
  >> 패치를 진행할 임시폴더로 복사합니다


4. 패치할 원본 파일 5개 복사
 
  (1) EBOOT.BIN  
  
    위치: rpcs3 설치폴더/dev_hdd0/game/BLJM61140/USRDIR/EBOOT.BIN  
    
  (2) LINKDATA.A  
  
      위치 : 원본게임폴더/PS3_GAME/USRDIR/LINKDATA_PS3  
      
  (3) LINKDATA.B  
  
      위치 : 원본게임폴더/PS3_GAME/USRDIR/LINKDATA_PS3  
      
  (4) LINKDATA.C  
  
      위치 : 원본게임폴더/PS3_GAME/USRDIR/LINKDATA_PS3  
      
  (5) LINKDATA.D  
  
      위치 : 원본게임폴더/PS3_GAME/USRDIR/LINKDATA_PS3  
      

[패치 방법]  

 == 모든 파일은 한 폴더내에 같이 있어야 합니다 ==  
 
0.패치할 임시폴더를 하나 만듭니다  

  예> c:/SGD  
  
 준비한 모든 파일을 여기에 넣습니다.  
 
1.한글패치를 "여기에 풀기"로 압축해제  

  반드시 반디집이나 7-zip을 이용해서 풀어야 합니다(알집은 제발 사용하지 마세요!)  
  

2.  패치할 파일 5개
  
  (1)  EBOOT.BIN  
  
    위치: rpcs3 설치폴더/dev_hdd0/game/BLJM61140/USRDIR/EBOOT.BIN  
    
    원본 MD5해시값  
    
     51a9e9194389b9b7081090fad19a1be0  
     
           
  (2)  LINKDATA.A  
  
        위치 : PS3_GAME\USRDIR\LINKDATA_PS3  
        
     원본 MD5해시값  
     
      e98aa8553c64c4ed8fefb5dc0780bc92  
      

  (3)  LINKDATA.B  
  
     위치 : PS3_GAME\USRDIR\LINKDATA_PS3  
     
     원본 MD5해시값  
     
      7bc3da5d58e66ec95a6624d4919d83e6  
      
     
  (4)  LINKDATA.C  
  
     위치 : PS3_GAME\USRDIR\LINKDATA_PS3  
     
     원본 MD5해시값  
     
      89c16a9e4bfd5a483a596888e4050166  
      

  (5) LINKDATA.D  
  
     위치 : PS3_GAME\USRDIR\LINKDATA_PS3  
     
     원본 MD5해시값  
     
      f7e4ad4262a5212f18e7fb122e3880b3  
      
 
MD5해시값은 동봉된 한글패치 파일중에  

md5cheker.bat 에 파일을 올려놓으면 표시됩니다  


3. 패치시작
 
  "이거_눌러서_패치해.bat" 를 누릅니다.  
  
  완료 메세지가 나올 때까지 기다립니다.  
  

5. 패치된 파일 복사
 
   현재폴더/patched 에 5개의 패치된 파일이 생성되어 있습니다
   
   원래 위치에 복사합니다.
   
   복사할 때 "덮어쓸거냐?"라고 물어보면 YES(네~)
   

 (1) 현재폴더/patched/EBOOT.BIN  
 
      위치로 복사: rpcs3 설치폴더/dev_hdd0/game/BLJM61140/USRDIR/EBOOT.BIN  
      
           
  (2) 현재폴더/patched/LINKDATA.A  
  
      위치로 복사 : 원본게임폴더/PS3_GAME\USRDIR\LINKDATA_PS3  
      

  (3) 현재폴더/patched/LINKDATA.B  
    
      위치로 복사 : 원본게임폴더/PS3_GAME\USRDIR\LINKDATA_PS3  
      

  (4) 현재폴더/patched/LINKDATA.C  
  
      위치로 복사 : 원본게임폴더/PS3_GAME\USRDIR\LINKDATA_PS3  
      
  (5) 현재폴더/patched/LINKDATA.D  
  
      위치로 복사 : 원본게임폴더/PS3_GAME\USRDIR\LINKDATA_PS3  
      
5. 게임 실행
 
   rpcs3 에뮬을 실행하고 원본 게임 폴더를 지정하면 게임이 실행됩니다~
   

====[DLC 설치]=====  

[DLC한글패치] 

압축비번  

2013년12월19일_v260629

 

[준비물]  

0. DLC한글패치
 
1. EDAT 해독도구 - TrueAncestor_EDAT_Rebuilder_v1.65
 
    다른 해독 도구가 있으면 그걸 사용하시면 됩니다.
   
    결과만 같다면 AI를 사용하셔도 OK
   
2. DLC 설치파일
 

[패치방법]  

 * 모든 파일은 한 폴더내에 있어야 합니다 *
   
0. 패치작업하는 폴더 를 하나 만듭니다.
 
   예> C:\SGDP
   
2. 다운로드한 DLC한글패치의 압축을 해제합니다 "여기에 풀기"
 
    반드시 반디집이나 7zip을 이용하세여(알집 사용 금지)
  
4. rpcs3를 실행시켜 DLC를 설치합니다.
 
   설치를 완료했으면 이제 파일들을 모두 복호화해야 합니다
   
    위치 : rpcs3 설치폴더\dev_hdd0\game\NPJB00533\USRDIR\DLC
   
    TrueAncestor_EDAT_Rebuilder_v1.65 사용 (구글검색)
   
    사용법 (사용 전에 백신으로 검사 하세요)
   
    (1) 압축풀어 edat폴더를 만들고 dlc파일들을 넣습니다
   
    (2) rebuilder.exe 실행
   
    (3) 녹색글자창이 뜨면 차례대로 1누르고, a누르면
   
    (4) 파일 복호화 됩니다.
   
    복호화되면 EDAT폴더에 DAT확장자 파일들이 생성됩니다.
   
6. 복호된 파일들을 패치작업하는 폴더로 모두 복사합니다
 
    위치 : 패치작업하는 폴더
   

7. 한글패치 시작
 

 (1) 원본 파일 해시값 확인  
 
        "MD5값확인.bat" 눌러 아래와 같은 프롬그램을 띄워 해시값을 확인합니다
      
맞으면 - O표시 , 맞지 않으면 - X표시

(2) "이거_누르고_기다려.bat" 를 누릅니다.  

    완료메세지가 나올 때까지 기다립니다.
 

(3) 정상적으로 패치가 성공했다면  

    패치작업하는 폴더\patched 에 일괄 생성됩니다  
    
     이 파일들을 모두 복사하여  
     
    위치 : rpcs3 설치폴더\dev_hdd0\game\NPJB00533\USRDIR\DLC  
    
    에 붙여 넣고 게임을 실행하면 됩니다  
    
   
