# Project Management Tool
## Project Description
 * This tools is used to managing/scheduling some tiny team project effectively.

## Main Feature
 * This program is consisted of `Schedule Manager, Calendar, TaskList, Search, Timeline diagram`.
 * This diagram shows structure of our program.


 * Our program has real-time synchronization of database between all team members with Firebase Database.

## How to use
 * First, Login to our program with account registered in database.(We will not serve login in MVP version)
 * At the main dashborad,

## How to obtain and install the software
 * Clone our repository and just build.
 * The command to clone our repository is
 ```git clone https://github.com/pm-tool-se2019/Source```
 * You need to use `Maven` to install all dependency to execute our program.
 * If you use `intellij` IDE, you can get the dependency library easily.

## How to run our software
 * Just build and execute.

## How to report a bug
 * We are open to receive contribution or issues for our program.
 * Please don't hesitate to report a bug or to give an opinion to our project :).
 * Just write `issue` of gitHub repository. but, I recommend to write specified issues to get exact reply.

## Dependency
 * Our program uses `JavaFX`, `firebase4j`.


----

# Source
실제 개발된 소스 코드를 모아두는 곳입니다.

각 모듈별로 폴더를 만들고, 그 폴더 안에서 개발하면 될 것 같습니다.

저 같은 경우는 Schedule Management 파트를 담당해서 src.main.java.ScheduleMan 폴더를 사용하고 있습니다.

루트 디렉토리에는 모두가 공유해야 할 소스를 두면 될 것 같네요.

Firebase나 src.main.java.DataClass.Task 클래스 등등...

소스코드 저장해놓는 Repository가 없어서 직접 팠습니다.


여러분 화이팅


* fork 떠가서 개인 레포에서 작업후 어느정도 진척되면 마스터로 push 하는게 좋을 것 같습니다.
* src.main.java.DataClass.Task 클래스는 모든 모듈에서 사용해야 하는 공통적인 Class니 다 같이 고민해보고 수정해봅시다.
* readme나 모듈 구성등 수정할 사항이 있으면 언제든 코멘트 남기고 수정해주세요. 사실 저도 이렇게 협업하는건 첨이라 잘 모릅니다. ㅠㅠ

Written by 송준호(RE-A)
