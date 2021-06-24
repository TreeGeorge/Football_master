# Football_Master
공유서비스 플랫폼 개발자 양성과정 4조 Team Project



# 개요

[서비스명_url](https://www.naver.com/)

FootballMaster 서비스는 장소 대여 및 공유 플랫폼으로서 
사용자가 원할 때 언제든 풋살을 즐길 수 있도록 지원하는 서비스 입니다.

# 시연 영상

![서비스 데모 동영상 ](http://assets.uxbooth.com/uploads/2018/08/Column-Center-1.gif)

# 프로젝트 기획안

![이미지](https://i2.wp.com/d1dlalugb0z2hd.cloudfront.net/handbooks/agile-handbook/wireframe/01-youtube-wireframe-example.png?resize=800%2C528&ssl=1)
![이미지](https://i1.wp.com/d1dlalugb0z2hd.cloudfront.net/handbooks/agile-handbook/wireframe/02-newspaper-site-wireframe-example.png?resize=800%2C601&ssl=1)

# 서비스 구조

![이미지](https://user-images.githubusercontent.com/84691802/123191697-986b6200-d4dc-11eb-863a-495649f56ef9.png)

# Database Schema

![이미지](https://user-images.githubusercontent.com/84691802/123033074-19195800-d422-11eb-8349-5752f934457f.png)

# 개발 환경

- Java(version) , Spring, Mysql ...
- AWS( EC2, ...)


# API 목록

[API 상세](https://github.com/TreeGeorge/Football_master/blob/master/api.md)
- GET /matches
- GET /$filter/{id}/matches
- GET /matches/{id}
- GET /my
- PUT /users
- DELETE /users
- POST /login
- GET /logout
- POST /cash_charge
- POST /cash_refund
- POST /reservation/{match_id}
- POST /cancel/{match_id}
- GET /my_bank
- PUT /my_bank
- GET /my_matches
