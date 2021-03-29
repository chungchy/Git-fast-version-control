# Git
* [Git](Git.md) : 코드 버전 관리 프로그램 
![gitgithub](https://user-images.githubusercontent.com/53849793/112778449-8ade4180-907f-11eb-9d75-9d6df5984de9.png)

# git 사용하게 된 이유
## 1. 트랜드 
* **most commonly used** 
* **free, open source** 
* **lightning fast**
* **work offine**
* **easy and fast branching/merging**

## 2. 협업 관리 도구

![스크린샷 2021-03-29 오후 4 54 44](https://user-images.githubusercontent.com/53849793/112804561-86318180-90af-11eb-9835-5663c530a9c3.png)

## 3. 버전 관리 용이
차이는 파일이 변경 이력 별로 구분되어 저장<br>
비슷한 내용의 파일이라도 내용 전체가 동일하지 않으면 다른 파일로 구분하기 때문에 파일을 변경 사항 별로 구분해서 저장할 수 있습니다.<br>

![스크린샷, 2021-01-17 09-47-45](https://user-images.githubusercontent.com/53849793/112794747-59c33880-90a2-11eb-8efa-340709221176.png)



## 저장소 위치
* **원격 저장소(Remote Repository)** : 파일이 원격 저장소 전용 서버에서 관리되며 여러 사람이 함께 공유
* **로컬 저장소(Local Repository)** : 내 PC에 파일이 저장되는 개인 전용 저장소
 
## Staging Area

![image](https://user-images.githubusercontent.com/53849793/112796455-f2f34e80-90a4-11eb-9a47-4b1417652189.png)

## 스냅샷

Git은 데이터를 파일 시스템 스냅샷의 연속으로 취급하고 크기가 아주 작다. Git은 프로젝트의 상태를 저장할 때마다 파일이 존재하는 그 순간을 중요하게 여긴다.

<img src="https://git-scm.com/book/en/v2/images/snapshots.png">

> 시간순으로 프로젝트의 스냅샷을 저장.

## Branch

개발을 하다 보면 코드를 여러 개로 복사해야 하는 일이 자주 생긴다. 코드를 통째로 복사하고 나서 원래 코드와는 상관없이 독립적으로 개발을 진행할 수 있는데, 이렇게 독립적으로 개발하는 것이 브랜치다
