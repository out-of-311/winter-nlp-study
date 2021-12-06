



### Keyword

- **저장소 (Repository)** : 작업자가 변경한 모든 내용을 추적하는 공간
- **작업 트리 (Working Tree)** : 저장소를 어느 한 시점을 바라보는 작업자의 현재 시점이다.
- **체크 아웃 (Checkout)** : 작업자의 작업트리를 저장소의 특정 시점과 일치 하도록 변경하는 작업
- **스테이징 영역** : 저장소에 커밋하기 전에 커밋을 준비하는 위치 (변경사항을 적용하기 전에 한번 더 변경사항을 정리하고 다듬을수 있는 기회를 제공한다. 변경사항을 추가하기 위해서는 git add 를 사용한다. 커밋 예정인 변경사항이 있다고 보면 된다.)
- **브렌치(branch)** : 브랜치라는 것은 하나의 개발 라인을 의미 한다.
한개의 프로젝트에서도 여러개의 개발 라인이 존재 할 수 있다. 가장 기본이 되는 master branch에서 버그 수정이나 특정 기능을 추가하기 위해서 개발라인을 따로 두고 작업할 수 있다.
이러한 브랜치에는 HEAD(branch head)라는 것이 있는데 이는 한개의 브랜치 내에서 가장 최근에 커밋이 된 reference이다. 예를 들면 branch apple에 3개의 commit이 있는데 이중에 가장 최근에 추가된 커밋이 HEAD가 된다.
- **master** : master 브랜치는 복사해온 저장소 내의 HEAD의 복사본이다.
- **origin** : origin 은 단지 git가 복사해 온 저장소를 가리키기 위해 기본적으로 사용하는 이름





### FAQ

#### Origin 

   원격 저장소의 이름입니다. 

​    원격저장소 시간때 원격저장소 추가 명령어는

​    git remote add <이름> <url>로 붙인다고 말씀드렸죠? :)

​    마찬가지로 git remote add origin <url> 형식으로 원격저장소를 추가하거나

​    git clone을 통해 원격저장소를 복사한다면

​    자동으로 origin이라는 이름의 원격저장소가 등록되게 됩니다.



#### master :

   브랜치 중 가장 중심이 되는 기본적인 branch를 master 브랜치라고 부릅니다



#### HEAD :

   현재 내가 어떤 작업공간에 있는지를 나타냅니다. 

​    예를 들어 만약 제가 master 브랜치에서 작업을 하고 있다면

​    제 HEAD는 master 브랜치에 있게 되는 것이고,

​    다른 작업을 위해 feature 브랜치를 만들어줬다면 

​    제 HEAD는 feature 브랜치에 있게 되는 겁니다 :)



#### 현재 현결된 remote(원격 저장소 표시)

```bash
git remote -v
```
