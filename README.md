# WutheringWaves_ProjectFiles
[![썸네일](https://youtu.be/-TJyNcVCfHY/0.jpg)](https://youtu.be/-TJyNcVCfHY)
* 명조: 워더링 웨이브 게임 모작 프로젝트입니다.

## 개요
* 게임: 명조: 워더링 웨이브
* 작업 기간: 25.06.27 ~ 25.07.30
* 개발 인원: 3명

## 팀원
* 유호근: 플레이어 캐릭터
* 정민수(팀장): 몬스터
* 김미진: UI
  
## 기술 스택
* 설계
<br />![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)![Blender](https://img.shields.io/badge/blender-%23F5792A.svg?style=for-the-badge&logo=blender&logoColor=white)
* 개발
<br />![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white)![Rider](https://img.shields.io/badge/Rider-000000.svg?style=for-the-badge&logo=Rider&logoColor=white&color=black&labelColor=crimson)
* 관리
<br />![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## 자료
* [PDF 자료](https://drive.google.com/file/d/1h8Hx5mR7-9_z3KuZal0OurJLFKapWh9E/view?usp=sharing, "구현 내용의 문서화 파일입니다.")

## 핵심 구현
### 1. 대시, 점프
* GameAbilitySystem(GAS) 프레임워크로 액션 관계 정리
* 몽타주 변수를 통해 캐릭터마다 다른 애니메이션 출력 
* CharacterMovementComponent(CMC) 커스텀으로 자연스러운 루트모션 구축
### 2. 공격 스킬
* AbilitySystemComponent(ASC)가 보유한 태그로 등장 캐릭터 구분
* Find Nearest Actor 노드 응용으로 공격 대상 설정
* AnimNotifyState 응용으로 특정 타이밍에 동작 캔슬
### 3. 캐릭터 교체  
* AttributeSet 교체 기법으로 등장 캐릭터 스탯 동기화
* 캐릭터 교체 시 카메라 회전 값, 가속도, TimeDilation 설정으로 이전 캐릭터 상태 유지

## 해당 프로젝트 파일은 에셋이 제외되어 플레이가 불가합니다!
