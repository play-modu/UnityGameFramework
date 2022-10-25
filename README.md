## HOMEPAGE

- **English** - Coming soon.
- **단순화 된 중국어** - [https://gameframework.cn/](https://gameframework.cn/)
  - **QQ 讨论群** 216332935

---

![Game Framework](https://gameframework.cn/image/gameframework.png)

---

## Game Framework 간단한 소개

게임 프레임 워크는 유니티 기반 게임 프레임 워크입니다. 주로 게임 개발 프로세스에서 일반적으로 사용되는 모듈을 캡슐화합니다. 개발 프로세스를 크게 표준화하고 개발을 가속화하며 제품 품질을 보장합니다.
최신 버전의 Game Framework에는 다음 19 개의 내장 모듈이 포함되어 있으며 개발자를위한 더 많은 확장 모듈을 개발할 것입니다.

1. **글로벌 구성 (Config)** - 플레이어의 초기 속도, 게임의 초기 볼륨과 같은 글로벌 읽기 전용 게임 구성을 저장하십시오.

2. **데이터 노드 (Data Node)** - 게임을 실행할 때 다양한 데이터를 관리하기 위해 트리 구조 형태로 모든 유형의 데이터를 저장하십시오.

3. **데이터 시트 (Data Table)** - 게임 데이터를 테이블 형식 (예 : Microsoft Excel) 형태로 구성한 후이 데이터 테이블을이 모듈과 함께 사용하십시오. 데이터 테이블의 형식을 사용자 정의 할 수 있습니다.
4. 
5. **디버거 (Debugger)** - 게임이 Unity 편집기에서 실행되거나 개발 모드에 의해 출시되면 디버거 창이 런타임 로그, 디버깅 정보 등을 촉진하기 위해 나타납니다. 사용자는 디버거 창에 기능을 쉽게 등록하여 사용할 수 있습니다.

5. **다운로드 (Download)** - 다운로드 파일의 기능을 제공하고 실종 연속성을 지원하며 허용 가능한 여러 다운로더를 동시에 다운로드 할 수 있음을 지정하십시오. 이 모듈은 리소스를 업데이트 할 때 적극적으로 호출됩니다.

6. **실재 (Entity)** - 게임 장면에서 생성 된 모든 객체를 엔티티로 정의합니다. 이 모듈은 숨겨진 엔티티 표시, 교수형 엔티티 (예 : 교수형 무기, 마운트 또는 다른 엔티티 잡기)와 같은 관리 엔티티 및 엔티티 그룹의 기능을 제공합니다. 엔티티가 사용 된 후에는 즉시 파괴되지 않아서 다음 재사용을 기다릴 수 있습니다.

7. **이벤트 (Event)** - 게임 논리 모니터링 및 입사 메커니즘 던지기. 게임 프레임 워크의 많은 모듈은 작업을 완료 한 후 구축 된 이벤트를 던지고 이러한 이벤트를 듣게되면 게임 로직 간의 커플 링이 크게 완화됩니다. 사용자는 자신의 게임 로직 이벤트를 정의 할 수도 있습니다.
8. 
9. **파일 시스템 (File System)** - 가상 파일 시스템은 유사한 디스크의 개념을 사용하여 산란 된 파일 중앙에서 중앙에서 산란 된 파일을 관리하고, 리소스로드 중에 생성 된 메모리 할당을 최적화하며, 리소스에 로컬 조각을로드 할 수도있어 리소스로드의 성능을 크게 향상시킬 수 있습니다.

9. **유한 상태 기계 (FSM)** - 제한된 상태 머신을 생성, 사용 및 파괴하는 기능을 제공하며 제한된 상태 머신 메커니즘에 적합한 일부 게임 로직을 제공합니다.이 모듈을 사용하는 것이 좋습니다.

10. **현지화 (Localization)** - 현지화 기능을 제공합니다. 즉, 우리는 일반적으로 다중 언어라고합니다. 현지화 측면에서 게임 워크는 텍스트의 현지화를 지원할뿐만 아니라 모든 리소스의 현지화를 지원합니다. 예를 들어, 게임에서 불꽃 놀이를 릴리스하면 몇 가지 언어를 더 만들 수 있습니다. 특수 효과와 영어 버전은 특별합니다. "새해 복 많이 받으세요"의 효과.

11. **회로망 (Network)** - 소켓 긴 연결을 사용하는 기능을 제공합니다. 현재, 우리는 TCP 프로토콜을 지원하며 동시에 두 버전의 IPv4 및 IPv6과 호환됩니다. 사용자는 여러 개의 연결을 설정하여 동시에 여러 서버와 통신 할 수 있습니다. 예를 들어, 기존의 게임 서버를 연결하는 것 외에도 음성 채팅 서버를 연결할 수도 있습니다. Protobuf와 같은 프로토콜 라이브러리에 액세스하려면 패킷 클래스에서 파생되어 자신의 메시지 패키지를 구현하는 한 사용할 수 있습니다.

12. **객체 풀 (Object Pool)** - 객체 고도 풀의 기능을 제공하여 자주 생성을 피하고 다양한 게임 객체를 파괴하고 게임의 성능을 향상시킵니다. 객체 풀 자체를 사용하는 것 외에도 사용자는 자신의 객체 풀을 쉽게 만들고 관리 할 수 ​​있습니다.

13. **프로세스 (Procedure)** - 런타임 동안 게임을 통해 실행되는 제한된 상태 머신입니다. 프로세스를 통해 다른 게임 상태를 선포하는 것은 매우 좋은 습관이 될 것입니다. 온라인 게임의 경우 리소스 프로세스를 확인하고 리소스 프로세스를 업데이트하고 서버 목록 프로세스를 선택하고 서버 프로세스를 선택하고 서버 프로세스에 로그인하고 역할 프로세스를 작성해야 할 수도 있습니다. 게임에서 메뉴 프로세스와 게임을 선택하려면 실제 게임 플레이 프로세스를 전환하십시오. 프로세스를 늘리려면 ProcessBase 클래스에서 파생되고 고유 한 프로세스를 구현하는 한 프로세스를 사용할 수 있습니다.

14. **자원 (Resource)** - 플레이어의 경험을 보장하기 위해 동기식 방법으로 리소스로드를 권장하지 않습니다. 게임 프레임 워크는 완전한 비동기로드 리소스 시스템 세트를 사용하므로 비동기로드 리소스의 인터페이스 만 제공됩니다. 간단한 데이터 테이블, 현지화 된 사전 또는 복잡한 엔티티, 장면 및 인터페이스에 관계없이 비동기로드를 사용합니다. 동시에 게임 프레임 워크는 기본 메모리 관리 전략을 제공합니다 (물론 자체 메모리 관리 전략도 정의 할 수도 있음). 대부분의 경우 GameObject를 사용하는 과정에서 자신없이 인스턴스화하거나 파괴 할 수도 있습니다.

15. **장면 (Scene)** - 여러 시나리오를 동시에로드하거나 언제든지 장면을 제거 할 수있는 장면 관리 기능을 제공하여 장면의 하위로드를 쉽게 알 수 있습니다.

16. **구성 (Setting)** - 키 -값 쌍의 형태로 플레이어 데이터를 저장하거나 UnityEngine.playerPrefs를 캡슐화하거나 이러한 데이터를 디스크에 직접 저장하십시오.

17. **소리 (Sound)** - 관리 사운드 및 사운드 세트의 기능을 제공합니다. 사용자는 사운드, 2D 사운드 또는 3D 사운드의 볼륨을 사용자 정의하거나 심지어 물리적 움직임에 직접 바인딩하여 엔티티를 따를 수도 있습니다.

18. **상호 작용 (UI)** - 숨겨진 인터페이스 표시, 활성화 인터페이스, 인터페이스 레벨 변경 등과 같은 관리 인터페이스 및 인터페이스 그룹의 기능을 제공합니다. UiformLogic 클래스에서 파생되고 자체 인터페이스 클래스를 구현하는 한 UGUI 또는 기타 유형의 UI 플러그인 (예 : NGUI)에 구축 된 Unity의 UNITY 여부. 인터페이스를 사용한 직후에 인터페이스가 파괴되지 않을 수 있으며, 다음 re -use를 기다릴 수 있습니다.

19. **Web 물어보기 (Web Request)** - 짧은 연결 기능을 제공하십시오. 서버에 요청을 보내고 GET 또는 Post 메소드로 응답 데이터를 얻을 수 있습니다. 여러 웹 요청자가 동시에 요청을 할 수 있도록 지정할 수 있습니다.

---

## INTRODUCTION

Game Framework is literally a game framework, based on Unity game engine. It encapsulates commonly used game modules during development, and, to a large degree, standardises the process, enhances the development speed and ensures the product quality.

Game Framework provides the following 19 builtin modules, and more will be developed later for game developers to use.

1. **Config** - saves some global read-only game configurations, such as the player's initial speed, the initial volume of the game, etc.

2. **Data Node** - saves arbitrary types of data within tree structures in order to manage various data during game runtime.

3. **Data Table** - is intended to invoke game data in the form of pre-configured tables (such as Microsoft Excel sheets). The format of the tables can be customised.

4. **Debugger** - displays a debugger window when the game runs in the Unity Editor or in a development build, to facilitate the viewing of runtime logs and debug messages. The user can register their own features to the debugger windows and use them conveniently.

5. **Download** - provides the ability to download files. The user is free to set how many downloaders could be used simultaneously.

6. **Entity** - provides the ability to manage entities and groups of entities, where an entity is defined as any dynamically created objects in the game scene. It shows or hides entities, attach one entity to another (such as weapons, horses or snatching up another entity). Entities could avoid being destroyed instantly after use, and hence be recycled for reuse.

7. **Event** - gives the mechanism for the game logic to fire or observe events. Many modules in the Game Framework fires events after operations, and observing these events will largely decouple game logic modules. The user can define his own game logic events, too.

8. **File System** - the virtual file system, based on the concept of disks, manages scattered files in a centralized way, optimizes memory allocation when resources are loaded, and can even load segments of resources. These will drastically enhance the performance of resource loading.

9. **FSM** - provides the ability to create, use and destroy finite state machines. It’d be a good choice to use this module for some state-machine-like game logic.

10. **Localization** - provides the ability to localise the game. Game Framework not only supports the localisation of texts, but also assets of all kinds. For example, a firework effect in the game can be localised as various versions, so that the player will see a "新年好" - like effect in the Chinese version, while "Happy New Year" - like in the English version.

11. **Network** - provides socket connections where TCP is currently supported and both IPv4 and IPv6 are valid. The user can establish several connections to different servers at the same time. For example, the user can connect to a normal game server, and another server for voice chat. The 'Packet' class is ready for inheritance and implemented if the user wants to take use of protocol libraries such as ProtoBuf.

12. **Object Pool** - provides the ability to cache objects in pools. It avoids frequent creation and destruction operations of game objects, and hence improves the game performance. Game Framework itself uses object pools, and the user could conveniently create and manage his own pools.

13. **Procedure** - is in fact an FSM of the whole lifecycle of the game. It’d be a very good habit to decouple different game states via procedures. For a network game, you probably need procedures of checking resources, updating resources, checking the server list, selecting a server, logging in a server and creating avatars. For a standalone game, you perhaps need to switch between procedures of the menu and the real gameplay. The user could add procedures by simply subclassing and implementing the 'ProcedureBase' class.

14. **Resource** - provides only asynchronous interfaces to load resources. We don’t recommend synchronous approaches for better play experience, and Game Framework itself uses a complete system of asynchronous resource loading. We load everything asynchronously, including simple things like data tables and localisation texts, and complex things like entities, scenes and UIs. Meanwhile, Game Framework provides default strategies of memory management (and of course, you could define your own strategies). In most cases, you don't even need to call 'Instantiate' or 'Destroy' when using 'GameObject' instances.

15. **Scene** - provides features to manage scenes. It supports simultaneous loading of multiple scenes, and the user is allowed to unload a scene at any time. Therefore partial loading/unloading of scenes could be easily implemented.

16. **Setting** - stores player data in key-value pairs by either encapsulating UnityEngine.PlayerPrefs or by saving the data directly to the disk.

17. **Sound** - provides features to manage sounds and groups of sounds. The user could set the properties of an audio clip, such as the volume, whether the clip is 2D or 3D, and could even bind the clip to some entity to follow its position.

18. **UI** - provides features to manage user interfaces and groups of UIs, such as showing or hiding, activating or deactivating, and depth changing. No matter the user uses the builtin uGUI in Unity or other UI plugins (NGUI, for example), he only needs to subclass 'UIFormLogic' and implement his own UI logic. The UIs could avoid being destroyed instantly after use, and hence be recycled for reuse.

19. **Web Request** - provides features of short connections, supports GET and POST methods to send requests to the server and acquire the response data, and allows the user to send simultaneous requests to different servers.
