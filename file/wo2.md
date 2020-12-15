# 2주차 목표  

<br>  

> Menu  

- 시작화면, 게임화면, 점수화면, 총 3개의 화면이 있다. => 50%  


- 시작화면에는 Single play, Multi play, Game option, Tutorial라는 버튼 4개가있다. =>100%  



> Single play  

- Single play 클릭시 New game, load game 이 있다. =>80%  


- 유닛&ai 생성 및 좌표이동 and 공격가능 =>100%  




> Multi play  

- 멀티플레이 화면 & 구동 => 0%  




> 맵제작  


- 판게아 =>50%  





> main music 제작 => 50%  




> 국가 제작  
- 한국 =>0%  


<br><br>

설명:

유닛생성, 유닛 좌표이동 / ai 생성 및 좌표이동 and 공격까지 프로그래밍

화면제작은 start menu 보안 , Single play 제작, game option 제작

맵제작은 판게아를 제작할 예정이지만 필요하면 자료끌어올예정
국가제작은 한국을 제작할 예정
mainmusic은 자료선별해서 넣을예정  


<br> <br>  
# 3주차 목표  

프로그래밍

> scene 작업

-게임화면, 점수화면, 게임옵션 총 4개의 화면 제작완료하기 -> 70% (점수화면 미완성, 게임화면 맵 미완성)

-single play 모드에서 new game, load game 코딩완료하기 -> 100%

-multi play 구현 - > 0% 문제해결못함



공격모션 effect 구현 -> 0% 기술필요



플레이어 & ai 건설 기능 구현 -> 50% (현재 아이템창까지 구현완료)



> 추가내용

-> player 앉기, 대쉬, 점프, 카메라 상하좌우 구현  



======================================================



> 그래픽 부분



맵제작 -> 판게아 맵 완성 & 대륙맵 틀짜기 -> 70%(판게아 80%, 대륙맵틀 30%)





> 오디오 부분



메인 music 삽입 완성 & 서브bgm제작or삽입 -> 100%  

<br><br>
# 4주차 목표  


요구사항 (6주)

> Scene

시작화면, 게임화면, 점수화면, 총 3개의 화면이 있다.



시작화면에는 Single play, Game option, Tutorial 총 버튼 3개가있다.



SinglePlay

Player Controller part



walk, Run, Jump, Crouch, speed, Attack (Function implementation)

Camera part



main cam, weapon cam

Weapon part



Hand , HandController



Gun, GunController



Axe, AxeController



pickAxe, pickAxeController



Reload, FineSightMode



Sound part



Bullet firing_ sound

Axe_Hit_sound

pickAxe _Hit _sound

effect



Muzzle flash, Muzzle flash inner

Melee weapon flash, Melee weapon flash inner

Hit, Hit_Effect 구현



animal Part(ai)

animal Controller part



Move, Attack (animator Function implementation)



Ground part 

판게아, 대륙맵 구현

item part

item manager



bonFire , meat, water, firewood



> UI part

총알 갯수 UI 구현

Player의 Food, water, Hp 상태 구현

낮,밤 전환 구현



> System part



Save&Load 구현

Game option

volume setting

main sound, sub sound Ui 구현



sound manager

main sound, sub sound 기능 구현



> Tutorial

1단계: 인터페이스 설명&조작



2단계: 게임 규칙 설명



3단계: 내부플레이


> 프로그래밍



-single play 모드에서 item, build 기능 구현하기  - 50%(5주차 완성)





-single play 전투씬을 위한 ai prefeb 제작 완료 및 전투기능구현 - 100%

아래는 구현한 내용들



SinglePlay

Player Controller part



walk, Run, Jump, Crouch, speed, Attack (Function implementation)

Camera part



main cam, weapon cam

Weapon part



Hand , HandController



Gun, GunController



Axe, AxeController



pickAxe, pickAxeController



Reload, FineSightMode



Sound part



Bullet firing_ sound

Axe_Hit_sound

pickAxe _Hit _sound

effect



Muzzle flash, Muzzle flash inner

Melee weapon flash, Melee weapon flash inner

Hit, Hit_Effect 구현



> 그래픽







- 맵제작 완료(판게아, 대륙맵)  - 판게아 100%, 대륙맵 50%(5주차 완성)







-게임화면, 점수화면, 게임옵션 화면 제작완료하기 - 점수화면 미완성  나머지 100%







- 동물 prefeb 제작  -> 50% 완성 





오디오 부분



- 전투씬에 bgm 삽입 - 0%





+ 추가된 내용 

-> 총알 UI 제작완료

-> Player Status ui 제작완료

-> pickaxe <-> Rock 로직구현완료  


<br> <br>
# 5주차 목표  

 요구사항 (6주)



> Ground part -> 100% (대륙맵은 error 코드가 떠서 아직 삽입 불가)



판게아, 대륙맵 구현 





> item part -> 70%



item manager



-> bonFire , meat, water, firewood 





> UI part -> 100%



낮,밤 전환 구현







> Tutorial -> 50%



1단계: 인터페이스 설명&조작



2단계: 게임 규칙 설명



3단계: 내부플레이  

<br> <br>  

# 6주차 목표  

6주차 목표







요구사항 (6주)







> menu part -> 오류수정 x



-> 시작화면에서 판게아, 대륙맵 선택구현 











> build part 



->  item build 오류 수정 -> 오류수정중(70%)



-> water  구현 -> 90%











> System part -> 90%



-> Save and Load   single play 대입시키기











> Tutorial   -> 구현 x











1단계: 인터페이스 설명&조작







2단계: 게임 규칙 설명







3단계: 내부플레이




<br><br>

# 동영상  
[2주차영상](https://j.gifs.com/2xV2pP.gif)  
[3주차영상](<iframe src='//gifs.com/embed/3-ROEN1R' frameborder='0' scrolling='no' width='1920px' height='1052px' style='-webkit-backface-visibility: hidden;-webkit-transform: scale(1);' ></iframe>)  
[4주차영상]()  
[5주차영상]()  
[6주차영상]()  



