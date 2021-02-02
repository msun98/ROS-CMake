# ROS-CMake

만든 package를 build하기 위해서 catkin_make를 실행한 다음에, 수정된 사항을 적용해주기 위해

매번 $source ./devel/setup.bash를 쳐야 GKSEK.

​

그래서 ~/.bashrc 파일을 수정 -> 자동 실행해주는 방법


$ gedit ~/.bashrc

​

그리고 나서 파일 맨 아래에

source ~/catkin_ws/devel/setup.bash

를 추가.
