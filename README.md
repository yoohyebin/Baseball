# ⚾️ 야구 다이어리 RUSH!
<p align="center">
    <img width="500" alt="image" src="https://github.com/user-attachments/assets/5bb9cfbb-4608-4b74-bb27-41b260653d04">
</p>
  
>**개발기간: 2024.03 ~ 진행 중**

## 📖 프로젝트 소개
- RUSH! 는 야구를 좋아하는 사람들이 경기 결과를 기록하고, 이를 티켓 형태로 만들어 인스타그램에 공유할 수 있는 앱입니다.
- 사용자는 직접 경기 정보를 입력하고 이를 시각적으로 확인하며, 인스타그램 스토리에 손쉽게 공유할 수 있습니다.

## ☺️ 멤버 소개
|🪐Woozu (UI/UX 디렉터)|🌻Helia (CTO) |🗽NewYork (PM)|
|:---:|:---:|:---:|
|<img alt="" src="https://github.com/user-attachments/assets/d6f0ed8c-0891-4493-8451-d8af5c97b198" width="150">|<img alt="" src="https://github.com/yoohyebin.png" width="150">|<img alt="" src="https://github.com/NewYorkKim.png" width="150">|
|UI/UX 디자인, 기획|개발, 기획|개발, 기획|

---

## 🔧 Stacks 

### Environment
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=Xcode&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)               

### Development
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=Swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0086c8?style=for-the-badge&logo=Swift&logoColor=white)
![Realm](https://img.shields.io/badge/Realm-39477F?style=for-the-badge&logo=Realm&logoColor=white)

### Communication
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)

---
## ⭐ Main Feature
### 경기 기록
- 사용자는 경기 날짜, 장소, 팀, 점수 등의 정보를 입력해 경기를 기록할 수 있습니다.
- 기록한 경기는 티켓 형태로 변환되어 메인 화면에서 한눈에 확인 가능합니다.
  
### 인스타 스토리 공유
- 기록된 경기는 인스타그램 스토리로 공유할 수 있으며, 투명 배경의 스티커 형태로 제공되어 사용자가 자유롭게 디자인을 추가할 수 있습니다.
---

## 🐈‍⬛ Git Branch
[Git 전략](https://github.com/DevTillDie/ForestTori/wiki)

## 📂 Project Structure
```
├─ .swiftlint.yml
├─ BaseballApp.swift
├─ Info.plist
├─ Resource
│  ├─ Assets.xcassets
│  └─ fonts
└─ Source
   ├─ Model
   │  ├─ Team.swift
   │  └─ Ticket.swift
   ├─ Utils
   │  ├─ Component
   │  │  ├─ GradientProgressStyle.swift
   │  │  ├─ HLine.swift
   │  │  ├─ NextButton.swift
   │  │  ├─ OnboardingTag.swift
   │  │  ├─ TicketShape.swift
   │  │  └─ VisualEffectView.swift
   │  ├─ Extension
   │  │  └─ Date+.swift
   │  ├─ Manager
   │  │  └─ RealmManager.swift
   │  └─ ViewModifier
   │     ├─ SelectedCircle.swift
   │     └─ TicketStroke.swift
   ├─ View
   │  ├─ MainView.swift
   │  ├─ OnboardingView.swift
   │  ├─ TeamSelectionView.swift
   │  └─ Ticket
   │     ├─ InputTicket
   │     │  ├─ CompleteTicketView.swift
   │     │  ├─ FifthInputTicketView.swift
   │     │  ├─ FirstInputTicketView.swift
   │     │  ├─ FourthInputTicketView.swift
   │     │  ├─ InputTicketView.swift
   │     │  ├─ SecondInputTicketView.swift
   │     │  └─ ThirdInputTicketView.swift
   │     └─ TicketView.swift
   └─ ViewModel
      ├─ InputTicketViewModel.swift
      ├─ OnboardingViewModel.swift
      └─ TicketViewModel.swift
```
---

## 👩🏻‍💻 Role
- 서비스 기획
- UI 및 사용자 인터랙션 구현
- 인스타그램 공유 기능 구현
- 데이터 구조 설계 및 데이터베이스 구축
