# 🎓 신촌대 맛집전공 🎓
<img src = "https://github.com/Pork-Potatoes/Pork-Potatoes-Front/raw/main/food-major/src/assets/banner.png"/>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FPork-Potatoes%2FPork-Potatoes-Back&count_bg=%23E0755F&title_bg=%239E5D50&icon=&icon_color=%23E0755F&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

## 🍏 백엔드 팀원 소개
| [김민주](https://github.com/MINJU-KIMmm)                                                                                             | [김시연](https://github.com/siyeonkm)                                                                                              | [박현아](https://github.com/hak2711)                                                                                               | [이서정](https://github.com/seojunglee)                                                                                               |
|----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| <img src = "https://github.com/MINJU-KIMmm/GitHubTest/blob/main/image/porkProfile/KimMinju.jpeg"/> | <img src = "https://github.com/MINJU-KIMmm/GitHubTest/blob/main/image/porkProfile/KimSiyeon.jpeg"/> | <img src = "https://github.com/MINJU-KIMmm/GitHubTest/blob/main/image/porkProfile/ParkHyunah.jpeg"/> | <img src = "https://github.com/MINJU-KIMmm/GitHubTest/blob/main/image/porkProfile/LeeSeojung.jpeg"/> |
|                                                                                                    |                                                                                                     |                                                                                                      |                                                                                                      |

## 🍎 프론트엔드 팀원 소개
| [이해린](https://github.com/dazzlynnnn)                                                            | [이윤지](https://github.com/L-Yunji)                                                                | [정드림](https://github.com/dream0214)                                                               |
|----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|
| <img src = "https://github.com/MINJU-KIMmm/GitHubTest/blob/main/image/porkProfile/LeeHaerin.jpeg"/> | <img src = "https://github.com/MINJU-KIMmm/GitHubTest/blob/main/image/porkProfile/LeeYunji.jpeg"/> | <img src = "https://github.com/MINJU-KIMmm/GitHubTest/blob/main/image/porkProfile/JungDream.jpeg"/> |
| [마이페이지], [리스트페이지], <br/>헤더 컴포넌트, 리뷰 컴포넌트, 식당 컴포넌트 구현                | [메인페이지], 지도, 플로팅버튼 구현                                                                 | [메인페이지] [로그인팝업], [검색결과 페이지] 구현                                                    |

## 🍐 기술 스택
[![React](https://img.shields.io/badge/React-61DAFB?style=round-square&logo=React&logoColor=black)](https://ko.reactjs.org/)
[![Spring](https://img.shields.io/badge/Spring-6DB33F?style=round-square&logo=Spring&logoColor=white)](https://spring.io/)

## 🍊 라이브러리
1. lombok
2. spring web
3. spring data jpa
4. oauth2
5. spring boot test
6. spring session jdbc
7. spring security test

## 🍋 프로젝트 구조
### 폴더 
<pre>
<code>
├── 🗂 java
│   └── 🗂 com
│       └── 🗂 matzipuniv
│           └── 🗂 sinchon
│               ├── 📑 Application.java
│               ├── 🗂 config
│               │   └── 📑 JpaConfig.java
│               ├── 🗂 domain
│               │   ├── 📑 Addition.java
│               │   ├── 📑 AdditionRepository.java
│               │   ├── 📑 BaseTimeEntity.java
│               │   ├── 📑 Folder.java
│               │   ├── 📑 FolderRepository.java
│               │   ├── 📑 Image.java
│               │   ├── 📑 ImageRepository.java
│               │   ├── 📑 Menu.java
│               │   ├── 📑 MenuRepository.java
│               │   ├── 📑 Pin.java
│               │   ├── 📑 PinRepository.java
│               │   ├── 📑 Report.java
│               │   ├── 📑 ReportRepository.java
│               │   ├── 📑 Restaurant.java
│               │   ├── 📑 RestaurantRepository.java
│               │   ├── 📑 Review.java
│               │   ├── 📑 ReviewRepository.java
│               │   ├── 📑 TempMenu.java
│               │   ├── 📑 TempMenuRepository.java
│               │   ├── 📑 User.java
│               │   └── 📑 UserRepository.java
│               ├── 🗂 service
│               │   ├── 📑 FileHandler.java
│               │   ├── 📑 FileHandler1.java
│               │   ├── 📑 FolderService.java
│               │   ├── 📑 ImageService.java
│               │   ├── 📑 MenuService.java
│               │   ├── 📑 PinService.java
│               │   ├── 📑 ReportService.java
│               │   ├── 📑 RestaurantService.java
│               │   ├── 📑 ReviewService.java
│               │   ├── 📑 TempMenuService.java
│               │   └── 📑 UserService.java
│               └── 🗂 web
│                   ├── 📑 FolderApiController.java
│                   ├── 📑 ImageApiController.java
│                   ├── 📑 MenuController.java
│                   ├── 📑 PinApiController.java
│                   ├── 📑 ReportApiController.java
│                   ├── 📑 RestaurantApiController.java
│                   ├── 📑 ReviewApiController.java
│                   ├── 📑 TempMenuController.java
│                   ├── 📑 UserApiController.java
│                   └── 🗂 dto
│                       ├── 📑 AdditionResponseDto.java
│                       ├── 📑 FolderResponseDto.java
│                       ├── 📑 FolderSaveRequestDto.java
│                       ├── 📑 ImageResponseDto.java
│                       ├── 📑 MenuDto.java
│                       ├── 📑 PinResponseDto.java
│                       ├── 📑 ReportDto.java
│                       ├── 📑 RestaurantListResponseDto.java
│                       ├── 📑 RestaurantResponseDto.java
│                       ├── 📑 ReviewListResponseDto.java
│                       ├── 📑 ReviewRequestDto.java
│                       ├── 📑 ReviewResponseDto.java
│                       ├── 📑 TempMenuDto.java
│                       └── 📑 UserResponseDto.java
└── 🗂 resources
    ├── 📑 application.properties
    └── 🗂 static
        ├── 🗂 images
        └── 🗂 uploads
</code>
</pre>

### 설명
1. main/java/[프로젝트명]/config ▶️ Config
2. main/java/[프로젝트명]/domain ▶️ Entity, Repository
3. main/java/[프로젝트명]/service ▶️ Service
4. main/java/[프로젝트명]/web ▶️ Dto, Controller
5. main/java/[프로젝트명]/Application.java
6. main/resources/application.properties
7. main/resources/static/images ▶️ 리뷰에 들어가는 이미지
8. main/resources/static/uploads ▶️ 프로필 사진


## 🍌 데이터베이스 설계도(E-R diagram)
<img src = "https://github.com/MINJU-KIMmm/GitHubTest/blob/main/image/porkProfile/matzip-univ-db.png"/>

## 🍉 API 명세서
### [🔗 Link](https://www.notion.so/API-bd2954deae834891889daaf5085d8853)


