Sequence 객체는 문자열로 된 DNA RAN 단백질 서열 정보를 담음

>from Bio.Seq import Seq
>
>tatabox_seq = Seq("tataaaggcAATATGCAGTAG")
>print(tatabox_seq)

###### 메서드 테이블
1. 000.count("A") : A개수를 반환 
2. 000.split("기준문자") : 
3. 000.strip() : 양끝의 공백,엔터와 같은 문자를 제거
5. 000.startswith("문자") : 객체의 서열이 지정한 "문자"로 시작하는지 참, 거짓
6. 000.transcribe() : RAN서열로 전사
7. 000.translate() : 단백질 서열로 번역
8. 000.complement() : 상보적 서열 만듬
9. 000.reverse_complement() : 역상보적 서열을 만듬

## Sequence record 객체
