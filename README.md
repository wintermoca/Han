## MFC SDI를 기반으로 한 간단한 멀티테스킹 예제
1.Visual Studio를 열고 MFC SDI 프로젝트를 생성합니다.

2.CMainFrame 클래스에서 메뉴 항목을 추가하여 "New Thread"라는 항목을 만듭니다.

3."New Thread" 메뉴 항목을 처리하기 위해 OnNewThread() 함수를 CMainFrame 클래스에 추가합니다.

4.새 스레드에서 실행할 함수인 MyThreadFunction을 만듭니다.

5.스레드에서 실행할 작업을 MyThreadFunction 내부에 추가합니다.

6.프로그램을 빌드하고 실행하면 "New Thread" 메뉴 항목을 통해 새로운 스레드를 시작할 수 있습니다. 이렇게 하면 메인 스레드와 새로운 스레드가 병렬로 실행될 것입니다.
