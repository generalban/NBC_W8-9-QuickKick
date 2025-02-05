# NBC_W8-9 TeamProject

![QuickKickThumnail](https://github.com/user-attachments/assets/e180aaf2-c8e3-46bc-98c9-6a7a6c7c4c02)

## <img src="https://github.com/user-attachments/assets/69395a63-42be-4b6b-a85f-dbebaaceb7ac" width="30"> QuickKick

### Quick + KickBoard = QuickKick
**빠르게 킥보드를 찾아타는 앱!**

### 와이어프레임 & 브레인스토밍
- 🔗[와이어프레임](https://www.figma.com/design/JTTqG16POU5bwqaHtHvPcT/NBC_8-9_Design?node-id=0-1&t=x16GFIJlzrqpyz03-1)
- 🔗[브레인스토밍](https://www.figma.com/board/QEBn7ce3IFbRMrLfYlQJXD/NBC_8-9_Figjam?node-id=0-1&t=9y1MCvMFogiRjEb4-1)

## 👥 팀원 소개 및 역할
| 🎯Leader | 💻Development | 💻Development | 💻Development | 💻Development |
| :-: | :-: | :-: | :-: | :-: |
| **황석현** | **장상경** | **전지혜** | **이명지** | **반성준**
| 로그인 화면 | 킥보드 상세 페이지 | 킥보드 등록 페이지 | 킥보드 찾기 페이지 | 마이 페이지 |
| 회원가입 화면 | 메인 탭 바 |  | | 코어 데이터 관리 |

## 🔥 프로젝트 목표

### 팀 핵심 목표
- 필수 구현 사항을 모두 완료하기
- 각자 최소 1개 이상의 기능, UI 구현
- 협업을 위한 활발한 소통
- 마일스톤 준수하기
- 코드리뷰를 통한 협업 능력치 상승

### 기대 효과
- 협업을 통한 팀워크 향상
- 개인 역량 강화
- 데이터 구조 학습
- API 이해도 증가

## 💿 프로젝트 기술 스택

### 데이터 구조
- **아키텍처 패턴**: `MVC` 패턴
- **데이터 저장 방식**: `UserDefaults`, `CoreData`
- **데이터 전달 방식**: `Delegate` 패턴

### 프로젝트 구조도

<img width="800" alt="NBC_8-9_Figjam (2)" src="https://github.com/user-attachments/assets/e5368aca-e1bc-4c7c-8c6e-10b91fc031b5" />


### 프로젝트 흐름도

<img width="800" alt="NBC_8-9_Figjam (3)" src="https://github.com/user-attachments/assets/0a8dffe1-7f64-40d9-ab02-eba8e66cab03" />

## ⏰ 프로젝트 진행 일정

### 진행 기간
- **시작**: 12.13(금) 17:00
- **종료**: 12.20(금) 12:00 까지

### 스프린트
- **Sprint 1** : ~ 12.18(**수요일 오전**)
- **Sprint 2** : ~ 12.19(**목요일 오후**)

### 스크럼
- **오전 11시** 튜터님과 스크럼: 마일스톤 진척도 확인, 피드백
- **오후 5시** 팀원들과 스크럼: 금일 작업 내용, 진행도, 이슈 등 공유

## 📓 Git 컨벤션

### 커밋 컨벤션

| 커밋 유형 | 의미 |
| --- | --- |
| feat: | 새로운 기능  추가 |
| add: | Feat 의외의 부수적인 코드 추가 |
| file: | 새로운 파일 및 폴더 추가 |
| fix: | 버그, 오류 해결 |
| del: | 파일을 삭제하는 작업만 수행한 경우 |
| mod: | UI 수정 |
| comment: | 필요한 주석 추가 및 변경 |
| rename: | 파일 또는 폴더 명을 수정 |
| move:  | 프로젝트 내 파일이나 코드의 이동 |
| docs:  | README나 WIKI 등의 문서 개정 |
| proj: | 프로젝트 관련 설정 변경 |

### Git Flow

<img width="800" alt="NBC_8-9_Figjam (4)" src="https://github.com/user-attachments/assets/322d7cba-7074-4bfd-8591-f9a46becabac" />

### 브랜치 룰

1. **main 브랜치에 프로젝트 기본 세팅**
    - README 작성
    - .gitignore 파일 작성
    - 프로젝트 파일 생성(Xcode)
    - 코드베이스 기본 세팅(스토리보드 삭제, info 설정 등)
    - 프로젝트 Asset 추가(이미지, 컬러세트 등)
    - 프로젝트 디렉토리 분리(각 역할 별로 분리)
    - 코어 데이터 추가
    
2. **dev 브랜치 생성(main 브랜치를 기준으로)**
    - 메인 브랜치에 만들어진 내용을 복제
    - 작업 브랜치(Default)를 dev 브랜치로 설정
    
3. **팀원별 원격 브랜치 분리**
    - dev 브랜치를 기준으로 원격 브랜치를 분리
    - 세부적인 작업 내용은 로컬 브랜치로 분리
  
4. **PR-Merge 전략**
    - PR을 작성할 때는 신규 내용, 변경 내용, 문제점 등을 상세히 작성
    - 팀원 모두는 PR에 대해 코멘트를 작성
    - **2**명의 **`approve`** 필요

5. **모든 작업 완료 후 test 브랜치를 생성**
    - dev 브랜치의 내용을 test 브랜치로 복제
    - test 브랜치에서 프로젝트 버그 확인 및 수정
    - 필요에 따라 hotFix 브랜치를 생성하여 운영

6. **완성된 프로젝트를 main에 전달**
    - `test`브랜치의 작업 내용을 `main` 브랜치에 **스쿼시 머지**
    - 불필요한 브랜치 삭제
    - README 수정

## 🚨 트러블 슈팅


## 🛠️ 1. Core Data Fetch 문제
### 문제
`MyPageViewController`에서 Core Data Fetch 이후 데이터가 `KickboardSectionView`와 `HistorySectionView`에 표시되지 않는 문제 발생.

### 원인
- Core Data Fetch 후 UI 갱신 로직이 누락됨.
- Fetch한 데이터를 뷰로 전달하지 않음.

### 해결
Core Data에서 데이터를 Fetch한 후 `configureSections()` 메서드를 호출하여 데이터를 UI에 전달하고 갱신하도록 수정하였습니다.

```swift
private func loadKickboards() {
    do {
        kickboardData = try CoreDataManager.shared.context.fetch(Kickboard.fetchRequest())
        configureSections() // Fetch 후 UI 갱신
    } catch {
        print("킥보드 데이터를 불러오는 데 실패했습니다: \(error)")
    }
}
```


---

## 🛠️ 2. UserDefaults 데이터 초기화 문제
### 문제
`ProfileView`에서 사용자 정보가 항상 초기값("User1", "user1234@gmail.com")으로 표시되는 문제 발생.

### 원인
- `UserDefaultsManager`의 `getUser()` 메서드 호출 누락.
- 사용자 정보 저장 로직이 제대로 작동하지 않음.

### 해결
`UserDefaultsManager`를 통해 사용자 정보를 가져오고 닉네임 변경 시 데이터를 저장하도록 수정하였습니다.




---

## 🛠️ 3. 더미 데이터 UI 반영 문제
### 문제
`HistorySectionView`에 전달한 더미 데이터가 UI에 표시되지 않는 문제 발생.

### 원인
- `HistorySectionView`의 `configure(with:)` 메서드가 호출되지 않음.

### 해결
`configure(with:)` 메서드를 호출하여 더미 데이터를 전달하고 UI를 업데이트하도록 수정하였습니다.


---

## 🛠️ 4. KickboardSectionView 버튼 액션 문제
### 문제
"내가 등록한 킥보드 >" 버튼 클릭 시 상세 화면으로 이동하지 않는 문제 발생.

### 원인
- `KickboardSectionView`의 `configure` 메서드에서 `onTap` 클로저 설정이 누락됨.

### 해결
클로저를 설정하여 버튼 클릭 시 상세 화면으로 이동하도록 구현하였습니다.


---

## 🛠️ 5. Core Data 데이터 필터링 문제
### 문제
"내가 등록한 킥보드"에서 올바른 데이터가 표시되지 않는 문제 발생.

### 원인
- Core Data Fetch Request에서 `NSPredicate` 설정이 누락됨.

### 해결
`isOccupied` 필터를 추가하여 Fetch된 데이터가 올바르게 필터링되도록 수정하였습니다.


---

## 🛠️ 6. ModalViewDelegate 미구현 문제
### 문제
`ModalViewDelegate` 프로토콜의 필수 메서드가 구현되지 않아 컴파일 오류가 발생.

### 원인
- `AddKickboardViewController`와 `MyKickboardDetailViewController`에서 필수 메서드가 누락됨.

### 해결
필수 메서드를 구현하여 컴파일 오류를 해결하였습니다.


---

## 🛠️ 7. 로그아웃 후 화면 전환 문제
### 문제
로그아웃 이후 로그인 화면으로 전환되지 않는 문제 발생.

### 원인
- 로그아웃 후 새로운 Root View Controller 설정 누락.

### 해결
`LoginViewController`를 Root View Controller로 설정하여 로그아웃 이후 화면이 전환되도록 구현하였습니다.


---

## 🛠️ 8. UI 레이아웃 문제
### 문제
`HistorySectionView`와 `KickboardSectionView`의 UI 간격 및 레이아웃이 어긋나는 문제 발생.

### 원인
- AutoLayout 제약 조건에서 상하 간격 및 좌우 마진이 통일되지 않음.

### 해결
AutoLayout 제약 조건을 조정하여 간격 및 마진을 통일하였습니다.

---

## 🛠️ 9. UIButton offset 문제
### 문제
![Screenshot 2024-12-16 at 17 36 05](https://github.com/user-attachments/assets/deaa3c29-4a08-4040-98f6-03cb3f06ae77)
<br>`systemImage`로 구성한 `UIButton`에 `backgroundColor`를 지정했을 때 자동으로 `Baseline offset`이 생겨 원치 않는 흰 테두리가 생기는 문제
### 원인
`Baseline offset`이 `UIButton`의 default임
### 해결
```swift
button.imageView?.contentMode = .center
```
![Screenshot 2024-12-19 at 21 18 44](https://github.com/user-attachments/assets/1fc1c21e-800c-4178-b645-0a93e4395a2a)
<br>버튼 내 이미지 뷰가 `button`의 `bounds`의 중앙에 있겠다는 명령으로, `baseline offset`을 무시하게 됨.

---

## 🛠️ 10. addressLabel font 문제
### 문제
![Screenshot 2024-12-19 at 21 13 00](https://github.com/user-attachments/assets/850b4e6d-d689-4f3c-ae9a-58cb8713296a)
<br>주소가 길어질 경우 `label.text`가 컨테이너 밖으로 벗어나는 문제
### 원인
- `label.font`가 정적인 값을 가짐
- `label`의 `leading`과 `trailing`에 대한 제약조건이 걸려있지 않음
### 해결
```swift
label.adjustsFontSizeToFitWidth = true
```
```swift
addressLabel.snp.makeConstraints {
    $0.leading.equalToSuperview().offset(8)
    $0.trailing.equalToSuperview().offset(-8)
}
```
![Screenshot 2024-12-19 at 21 20 28](https://github.com/user-attachments/assets/e1ef323e-1579-4f88-b063-b7a73f6a6e48)

---

## 🛠️ 11. 터치 이벤트 전달 문제
### 문제

![](https://velog.velcdn.com/images/myungjilee/post/5fe4146c-b37b-478d-a844-d48ca953f375/image.gif)

`SearchLocationBarView`에서 `searchResultsTableView`의 `cell`을 터치해도 터치 이벤트 메서드가 호출되지 않는 문제.


### 원인
- 터치 이벤트가 `searchResultsTableView`의 `cell`로 전달되는 것이 아니라 다른 뷰로 전달되는 것.

### 해결
- hitTest를 오버라이드 해 터치가 `searchResultsTableView`의 `cell` 영역 내에 발생하면 해당 뷰로 이벤트 전달하도록 수정.

```swift
    override func hitTest(_ point: CGPoint, with event: UIEvent?) -> UIView? {
        if !searchResultsTableView.isHidden {
            let convertedPoint = convert(point, to: searchResultsTableView)

            if searchResultsTableView.bounds.contains(convertedPoint) {
                if let hitView = searchResultsTableView.hitTest(convertedPoint, with: event) {
                    print("TableView cell hit at point: \(point)")
                    return hitView
                }
            }
        }

        return super.hitTest(point, with: event)
    }
```
---

## 🛠️ 12. 상세 페이지에서 데이터 수정 시 모달 버튼 비활성화 버그

### 문제

- 상세페이지에서 수정을 위해 모달뷰를 열면 해당 킥보드에 대한 정보(닉네임, 타입 등)를 가져오는데, 데이터를 수정해도 '등록하기' 버튼이 비활성화 되는 버그
- 텍스트 필드(닉네임)를 지우는 행동을 하면 버튼이 활성화 되는 현상 확인
- 타입 버튼을 선택해도 버튼은 비활성화 상태

### 원인

원인을 이해하려면 우선 '등록하기' 버튼의 활성화 조건을 이해해야 하는데, '등록하기' 버튼은 '닉네임' 텍스트 필드가 채워져 있고, '킥보드 타입'이 선택되어 있을 때 활성화 된다.
```swift
/// 등록하기 버튼을 활성화 하는 메소드
func activateButton() {
    guard self.typeSelected, self.haveNickNameText else {
        self.addButton.activateButton(false)
        return
    }
        
    self.addButton.activateButton(true)
}
```
이 때, `typeSelected`와 `haveNickNameText`는 델리게이트가 가진 프로토콜이고, 닉네임 텍스트 필드의 텍스트 수가 0보다 크고 킥보드 타입이 선택 되어 있을 때 `true`로 설정된다.
왜 활성화가 안될까 싶어서 브레이크 포인트를 걸고 출력을 해봤는데...

![스크린샷 2024-12-20 11 43 13](https://github.com/user-attachments/assets/059837c9-2731-4b16-8060-920cd58c51e7)

조건이 충족되지 않는 모습을 볼 수 있었다.
분명 메소드를 통해 `Bool` 값을 바꿔주도록 했는데 제대로 작동이 되질 않는다...

### 해결

메소드를 수정해보고 값도 수정해 보고 여러 시도를 했지만 제대로 동작하지 않아서
결국 직접 값을 수정하도록 메소드를 수정하였다.

```swift
/// 내 킥보드 관리에서 cell을 탭했을 때 킥보드 유형과 별명을 전달 받는 메소드
func editKickboardData(_ type: Bool, _ text: String, _ id: NSManagedObjectID) {
    self.kickboardID = id
    self._sendNickName = text
    self._kickboardType = type
    self._haveNickNameText = true
    self._typeSelected = true
    self.typeButton.updateData(type)
    self.textField.updateData(text)
    self.addButton.modalMode = .edit
    self.addButton.activateButton(true)
}
```
