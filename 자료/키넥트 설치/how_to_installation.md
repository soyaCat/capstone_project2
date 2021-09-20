## TESTED ON ROS MELODIC
## 키넥트 V2를 설치하는 방법

1. opencv4 버전에서도 사용가능하게끔 코드를 개조한 버전입니다.
2. 우선 opencv4를 설치해줍니다.
3. ROS를 설치해줍시다.
4. 다음 링크의 가이드에 따라 kinect드라이버를 설치해줍니다. (https://github.com/OpenKinect/libfreenect2)
5. 3.의 링크 대신 "자료/키넥트 설치/"의 libfreenect2-master.zip을 이용해도 무방합니다.
6. 다음 링크(https://github.com/code-iai/iai_kinect2) 의 가이드에 따라 ROS패키지를 설치해주어야 하는데, 해당 링크의 패키지는 opencv2를 대상으로 되어 있습니다.
7. 따라서 실제 설치는 자료실의 iai_kinect2.zip을 이용해서 설치해주도록 합시다.
8. 해당 링크의 roslaunch가 안먹힙니다. src폴더의 키넥트브릿지 폴더의 launch파일로 직접 이동해서 실행시켜주도록 합시다.