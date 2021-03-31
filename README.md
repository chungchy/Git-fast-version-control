# Git
* [Git](Git.md) - git sheet
![gitgithub](https://user-images.githubusercontent.com/53849793/112778449-8ade4180-907f-11eb-9d75-9d6df5984de9.png)

# git 사용하게 된 이유
## 1. 트랜드 
* **most commonly used** 
* **free, open source** 
* **lightning fast**
* **work offline**
* **easy and fast branching/merging**

## 2. 협업 관리 도구

![112804561-86318180-90af-11eb-9835-5663c530a9c3](https://user-images.githubusercontent.com/53849793/113097445-dafd0580-9231-11eb-8c40-7f25b86243b8.png)


## 3. 버전 관리 용이
우리가 일반적으로 파일을 저장하는 것과 git 저장소에 저장하는 차이는 파일이 변경 이력 별로 구분되어 저장<br>
비슷한 내용의 파일이라도 내용 전체가 동일하지 않으면 다른 파일로 구분하기 때문에 파일을 변경 사항 별로 구분해서 저장할 수 있습니다.<br>

![스크린샷, 2021-01-17 09-47-45](https://user-images.githubusercontent.com/53849793/112794747-59c33880-90a2-11eb-8efa-340709221176.png)

> 한번쯤 경험해 봤을 법 한...
> 
<br>

# git 주요기능
## 저장소 위치
* **원격 저장소(Remote Repository)** : 파일이 원격 저장소 전용 서버에서 관리되며 여러 사람이 함께 공유
* **로컬 저장소(Local Repository)** : 내 PC에 파일이 저장되는 개인 전용 저장소
 
## Staging Area

![image](https://user-images.githubusercontent.com/53849793/112796455-f2f34e80-90a4-11eb-9a47-4b1417652189.png)

## 스냅샷

각 버전의 '차이점'을 저장하는 것이 아니라 버전을 저장할 때의 각각의 시점 전체를 하나의 '스냅샷'으로 저장합니다.

<img src="https://git-scm.com/book/en/v2/images/snapshots.png">

> 시간순으로 프로젝트의 스냅샷을 저장.

## Branch

코드를 통째로 복사하고 나서 원래 코드와는 상관없이 독립적으로 개발을 진행할 수 있는데, 이렇게 독립적으로 개발하는 것이 브랜치다

<br>

# 앱파트에서 사용한 git 플로우

![무제 002](https://user-images.githubusercontent.com/53849793/112917727-41086080-913e-11eb-8c7a-59fead60230c.jpeg)
> Development 브랜치 생성

![무제 003](https://user-images.githubusercontent.com/53849793/112917780-5a111180-913e-11eb-8a46-c25b808b4375.jpeg)
> 각 feature 브랜치 생성

![무제 004](https://user-images.githubusercontent.com/53849793/112919032-2daac480-9141-11eb-8ded-c5d7dc0a83f0.jpeg)
> 각 feature 브랜치에서 개발 후 커밋

![무제 005](https://user-images.githubusercontent.com/53849793/112919049-37342c80-9141-11eb-9a23-001a24bc0b47.jpeg)
> Development 브랜치에 머지

Anchor 브랜치 https://github.com/chungchy/Android_AnchorEnglish/branches/active

<br>

# git 도입 후 변화
* **소스 관리**
* **코드 리뷰**
* **클린 코드**
* **버전 관리**
