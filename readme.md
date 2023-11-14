# cloud 9 에서 용량 부족 증가 방법
    1. nano resize.sh 실행
    2. resize.sh(메모장에서 오픈해서 내용 카피) 내용 paste 
    3. 저장( ctrl+x) -> y(es) -> 엔터
    4. chmod +x resize.sh
    5. ./resize.sh 20
        -> 로그 지난후 계속 화면이 머물러 있으면
        -> 엔터 계속 치고, 반응없으면 ctrl + C로 빠짐
        -> 20 용량(총용량 30G가 무료)
    6. df -h (새로운 터미널에서도 확인 가능)
