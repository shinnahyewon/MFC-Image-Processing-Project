# MFC-Image-Processing-Project
MFC Image Processing Project

■ 기능 설명
1) FFT(Fast Fouier Transform)
 - DFT의 계산량의 한계를 극복하기 위한 연산 알고리즘
 - DFT의 계산 과정에서 대칭성과 주기성을 사용하여 연산량을 줄이는 변환

2) IFFT((Inverse Fast Fourier Transform)
 - FFT의 역변환 알고리즘
 - 주파수 영역에서 다시 시간 영역으로 변환

3) 컨볼루션 마스크
 - 고주파 영역의 성분을 제거하여 블러링 처리를 하거나,
 - 저주파 영역의 성분을 제거하여 에지 영상 처리 가능

4) 잡음 제거
 - 잡음제거 알고리즘에는 평균 필터, 메디안 필터, 가우시안 스무딩 필터가 존재

5) 히스토그램
 - 영상의 명암값 프로필을 보여주기 위해 사용
 - 각 픽셀의 밝기값을 센 후 빈도수를 측정, 명암값 분포에 대한 정보를 제공
 - 히스토그램의 분포가 왼쪽으로 치우쳐있을 경우 화소의 밝기 값이 작아 영상이
   어둡고, 오른쪽으로 치우친 경우 픽셀값이 커서 영상이 밝음을 알 수 있음.
   
6) 임계 값에 의한 영상 이진화
 - 이미지의 화소 밝기 값을 센 후,
 - 일정한 임계값을 기준으로 임계값보다 낮은 경우 0(검정색),
 - 임계값 이상이면 픽셀값을 255로 설정하여 흰색이 출력되도록 하는 방식

 - ![image](https://github.com/shinnahyewon/MFC-Image-Processing-Project/assets/161293023/0ca707c4-9390-48e2-873a-9f7dcc66a204)
