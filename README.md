
## 라즈베리파이 얼굴인식 및 경보


# 구현방법

1. 라즈베리파이 카메라를 사용하여 얼굴인식
  - 라즈베리파이 서버 : cmake, dlib 사용
  - 얼굴인식 : opencv, harrcascade 사용

2. 사람 얼굴인식이 되었다면
  - 부저를 사용하여 경보
  - 셀레니움을 바탕으로 남자와 여자에 대한 인공지능 모듈을 생성
    (남자에 가까우면 LED에 파란색, 여자에 가까우면 LED에 빨간불)
