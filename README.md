# -CSEG483-CSE5483-HW-2-Matrix-Multiplication
[CSEG483/CSE5483] HW 2: Matrix Multiplication

**Download Link:https://programming.engineering/product/cseg483-cse5483-hw-2-matrix-multiplication/**

Description
5/5 – (2 votes)
제출 마감: 5월 20일(월) 오후 8시 정각 이전에 조교가 사이버 캠퍼스에 공지한 방식으로 제출

참고: LATE 없음

이번 숙제에서는크기가 큰 두 행렬 A와 B를곱하여 C를계산하는문제를 GPU를사용하여 가속하는문제에 대하여 실습하여 본다. 다음 7 가지 방법을 구현한 후, 세 가지 서로다른 크기의행렬에 대하여 계산 시간을 측정한후 그 내용을분석하라.

[방법 1] Host에서 작동하는함수를 가급적 효율적으로 구현하라. (MM HOST)

[방법 2] Device에서 shared memory를사용하지 않는 기본적인함수를 가급적 효율적으로 구현하라.

(MM DEVICE GM)

[방법 3] Device에서 shared memory를사용하는함수를 가급적 효율적으로 구현하라. (MM DEVICE SM)

[방법 4] Device에서 shared memory를사용하고 “More-Work-per-Thread” 아이디어를사용하여 최적화 한함수를가급적 효율적으로 구현하라. (MM DEVICE SM MWPT)

[방법 5] Device에서 Tensor core를 기반으로 shared memory를사용하지 않는함수를 가급적 효율적으로 구현하라. (MM DEVICE TC GM)

[방법 6] Device에서 Tensor core를 기반으로 shared memory를사용하여 최적화한함수를 가급적 효율 적으로 구현하라. (MM DEVICE TC SM)

[방법 7] Device에서 cuBlas에 기반을 둔 함수를 가급적 효율적으로 구현하라. (MM DEVICE CUBLAS)

제출물: 자신이 구현한 코드를이름이 HW 2 학번인 디렉터리 아래의 Visual Studio 프로젝트를생성한 후, zip 으로 압축하여 제출할것.

자신이작성한코드: Visual Studio 2022를 통하여 확인할 수 있도록 위의 directory를 제출하되 .vs 파일 등코드수행에 불필요한 파일들은 반드시 제거한 후 제출할 것.

프로그램 실행결과: 자신의 코드를 실행한 결과를 증빙할 수 있는자료(예를 들어, 콘솔 윈도우의 내용을 캡춰한영상)를보고서에포함할것.

보고서: 자신의 실험 결과를 바탕으로분석한 내용을 기술할 것.

참고:

입력 행렬은 random number를사용하여 생성한후, 각방법이올바른계산결과를산출하는지 반드시 확인하라.

최소한한 예는자신의컴퓨터에서 허용하는 가급적 크기가큰 행렬을사용할 것.

각방법의 실험 결과를자신만의 방식으로의견을 제시하라.

– [CSEG483/CSE5483] 기초 GPU 프로그래밍 HW 2 (2024년 5월 20일 (월) 오후 8:00 마감) –
