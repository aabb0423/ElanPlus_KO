엘란 플러스 한글 패치
대상: PlayStation 일본판 SLPS-02759 / Elan Plus (Japan)

xdeltaGUI 적용 방법
1. 배포 ZIP의 압축을 풉니다.
2. xdeltaGUI 또는 xdeltaUI의 Apply Patch / Apply 화면을 엽니다.
3. 다음 파일을 지정합니다.
   Patch: ElanPlus_KO.xdelta
   Source File: 수정하지 않은 일본판 원본 BIN
   Output File: ElanPlus_KO.bin (원본과 다른 출력 경로)
4. Apply 또는 Patch 버튼으로 적용합니다.
5. 생성된 ElanPlus_KO.bin과 동봉된 ElanPlus_KO.cue를 같은 폴더에 둡니다.
6. 에뮬레이터에서 ElanPlus_KO.cue를 엽니다.

패치는 BIN 파일에 적용합니다. CUE나 압축 파일에 적용하지 않습니다.
출력 BIN 이름을 바꾸면 CUE 첫 줄의 BIN 이름도 같은 이름으로 고칩니다.
패치 오류가 나면 아래 원본 크기와 해시가 일치하는지 확인합니다.

필요한 원본 BIN
파일명 예: Elan Plus (Japan).bin
크기: 581,621,376바이트
MD5: 743a8dfa46d8d8f8b9aa49abbaf1b4ec
SHA-256: b5ef3e3671bc42efd7b7e267482ff18e5e1385ee7c43a5c769326efdde6b0abc

패치 적용 후 BIN
권장 이름: ElanPlus_KO.bin
크기: 581,621,376바이트
SHA-256: a6e5f22f0f77e5a632d04adf117cc2a57a423eddbdf9bdce30543ae05fedc167

반영 내용
추출 텍스트 11,470행, 시설·메뉴·이름 입력·결과·갤러리·인터뷰 UI,
프롤로그 자막, 월말·최종 시험 영상 9개의 일본어 카드,
불러오기 화면의 날짜·확인 선택지 정렬 수정을 포함합니다.

패치는 추가 압축 없는 표준 xdelta3 VCDIFF 형식입니다.
원본에 패치를 적용한 결과가 위 한글 BIN 해시와 일치함을 확인했습니다.

폰트: M갈무리 / https://github.com/MonadABXY/mgalmuri-font
폰트 라이선스: MGalmuri-OFL.txt
참고 툴: upstream-tools-LICENSE.txt
