쿼리문 규칙 위반
===============

처음 학원에서 공부할때, 그리고 팀 프로젝트를 진행할때 SQLSyntaxErrorException가 자주 발생하였습니다.

그 원인을 찾아보면 보통 세미콜론을 찍지 않는다거나 괄호 표시를 잘못 작성하는 등 이클립스에서 문법에 맞지 않게 코드를 작성하면 SQLSyntaxErrorException 가 발생하였습니다.

![SQLSyntaxErrorException](https://user-images.githubusercontent.com/74330505/118515408-537f3d80-b770-11eb-932b-c8d0208f8a40.png)

오라클 에러코드는 정말 다양하게 있었고 그 중 제가 가장 많이 발생시킨 에러코드는 ora-00900 이었습니다.

해결 : 오타와 세미콜론 등 오타 교정
