# rock-paper-scissors

# 가위바위보 게임 

## 프로젝트 개요
이 프로젝트는 웹캠을 통해 손모양을 인식하여 가위 바위 보를 선택하는 게임으로 컴퓨터가 임의로 선택한 것과 대결하여 가위 바위 보 승부 여부를 확인하는 게임입니다.
올인원 Pass! 인공지능 프로젝트 마스터 교육 과정에서 팀프로젝트로 진행하였습니다.

## 기여자
이 프로젝트에 기여하신 분들은 백송이, 장지연, 정문경, 허경입니다.

## 참고
생성형 AI 툴을 활용하여 코드가 작성되었고 테스트를 하면서 수정 보완하였습니다.

## Files
- camera.ipynb
  카메라 캡쳐 코드
- detect.py
  YOLO 모델을 이용하여 웹캠으로 들어오는 영상의 손모양에서 가위바위보를 인식하고 임의로 선택한 가위바이보를 멀티쓰레드로 처리하도록 구현한 코드
- generateModel.ipynb
  범용인식 YOLO모델에 가위바위보를 인식할 수 있도록 추가학습한 모델생성
- init.ipynb
  YOLO 모델 테스트 코드
- rps.ipynb
  가위바위보 인식
- reverse-data.py
  한쪽손모양으로 되어 있는 이미지 데이터를 반전시켜서 생성하는 코드
