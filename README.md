# Wandoo!
`Storyboard` `MVVM` `Lottie` `Local Notification` `CocoaPods`

#### ✨ 비대면 강의 완주 메이트, Wandoo!
> 비대면 강의를 들어야하는 모든 사람들을 위한 어플

<img src = "https://user-images.githubusercontent.com/22907483/158617103-529b5ddb-50a5-4899-a676-338412cad2bf.png" width= "30%"><img src = "https://user-images.githubusercontent.com/22907483/158617210-a851cc4a-648f-4797-ba51-c35e432cf98b.png" width= "30%">

> - 프로젝트 기간: 2021.03 ~ 2021.05  
> - Released: 2021.08
> - 개인 프로젝트

[<img src = "https://user-images.githubusercontent.com/22907483/158495296-80b90b26-9fb3-4933-96b5-a5953b30fb6c.png" width= "18%">](https://apps.apple.com/kr/app/wandoo/id1579146261)

## Service
- **강의 진도 체크**: 강의 수 만큼 TableViewCell이 생성되고 강의를 수강 후 체크를 함으로써 진도율을 확인할 수 있습니다. 강의를 모두 수강할 시 팡파레 애니메이션을 통해 완강의 기쁨은 두 배가 됩니다.  
- **강의 별 간단한 메모 저장**: 각 강 별로 강의 주제 혹은 잊지 말아야 할 간단한 메모 또한 저장할 수 있습니다.  
- **리마인드 알림**: 진도 체크를 잊지 않도록 원하는 시간에 리마인드 알림을 받을 수 있습니다.

## Wireframe
<img width="80%" src="https://user-images.githubusercontent.com/22907483/158619022-5ee56abd-54a3-4ccd-8091-375dd23b51ca.png">

## Skill
- Architecture
```swift
'MVVM'
```
- View
```swift
'Storyboard'
'Lottie'
```
- User Experience
```swift
'UNUserNotificationCenter'
'UINotificationFeedbackGenerator'
```
## View
### 1. 메인 화면
<img src = "https://user-images.githubusercontent.com/22907483/158623910-c2cdbef8-7d8e-491b-8ea6-737858aec5cc.PNG" width= "25%">
- 현재 수강 중 이거나 수강 완료한 수업들을 확인할 수 있습니다. 우측 하단의 '+' 버튼을 통해 강의 추가 페이지로 진입할 수 있으며, 우측 상단의 톱니바퀴 버튼을 통해 설정 페이지에 진입할 수 있습니다.  
- 강의를 왼쪽으로 슬라이드하여 바로 삭제할 수 있습니다.

### 2. 강의 추가
<img src = "https://user-images.githubusercontent.com/22907483/158623923-fe00c15d-680a-466c-ab44-63f261aece72.PNG" width= "25%">  
- 강의명, 강의 수, 수강 시작날짜를 기입한 후 강의를 추가할 수 있습니다.  

### 3. 강의 세부 페이지
<img src = "https://user-images.githubusercontent.com/22907483/158623932-47f7ce73-34ff-4bc2-9b03-3adab056fd1e.PNG" width= "25%">  <img src = "https://user-images.githubusercontent.com/22907483/158623794-eefea321-7dc5-4f44-b9c6-e734e6be934c.gif" width= "25%"> 
- 강의 진도를 직접 체크하고 관리할 수 있습니다. 테이블 우측을 클릭하면 체크 표시가 나타나고 이를 통해 진도율 관리를 할 수 있습니다.  
- 가운데 메모칸을 클릭하여 간단한 메모를 작성할 수 있습니다.  
- 만약 강의를 모두 수강한다면 팡파레 애니메이션이 실행됩니다.  
- 우측 상단의 ellipsis 버튼을 클릭하여 강의 정보를 수정하거나 강의를 삭제할 수 있습니다.

### 4. 강의 정보 수정
<img src = "https://user-images.githubusercontent.com/22907483/158623941-bdedd535-2a66-44e5-93be-2003852cc4ca.PNG" width= "22%">  <img src = "https://user-images.githubusercontent.com/22907483/158623947-ae9eabe4-3f77-432b-88ad-db8e3f019607.PNG" width= "22%">
- 강의명, 강의 수, 시작 날짜를 수정할 수 있습니다.  
- 만약 기존 강의 수 보다 수정된 강의 수가 적을 경우, 저장된 메모가 삭제될 수 있으므로 Alert창을 띄워서 다시 한 번 삭제 의사를 확인합니다.  
 
 ### 5. 리마인드 알림  
 <img src = "https://user-images.githubusercontent.com/22907483/158623936-f1d2998e-b3b7-4b76-8338-a10d8702328a.PNG" width= "25%">
 - 사용자가 알림 설정을 키고 원하는 시간을 설정하면 설정된 시간에 매일 리마인드 알림을 받을 수 있습니다.
 - 핸드폰 설정 - 앱 설정에서 알림이 꺼져있는 경우에는 자동으로 앱 내의 설정도 꺼지도록 설정했습니다.

## Update
- **ver 1.1**  
  - 이제 다크 모드에서도 Wandoo!를 사용할 수 있습니다!  
  - 강의 생성 후에도 강의 수를 수정할 수 있습니다.  
- **ver 1.1.2**  
  - 진도 체크 시 햅틱 반응 수정

## Extra Detail
- [ToyProject_Wandoo! 개발 일지](https://velog.io/@hope1053/series/ToyProjectWandoo)
