<div align="center">
  <a href="https://danggeun-market.vercel.app">
    <img height="120" src="./danggeun_market_logo.png" />
    <br /><br />
    <a display="block" href="https://danggeun-market.vercel.app">https://danggeun-market.vercel.app</a>
    <br /><br />
    <img height="700" src="./1.gif" />
  </a>
</div>

## Table of contents

- 🔥 [Built with](#built-with)
- 🌈 [Project](#project)
- 📑 [Pages](#pages)
- ⚙ [Features](#features)
- 📝 [License](#license)

## Built with

### Front-end

- `NextJS`
- `React`
- `Typescript`
- `SWR`
- `TailwindCSS`

### Back-end

- `PlanetScale`
- `Prisma`
- `Twilio`
- `SendGrid`
- `Iron Session`
- `Cloudflare Images`
- `Cloudflare Stream`

### Deploy

- `Vercel`
- `PlanetScale`
- `Cloudflare`

## Project

> 1. 로그인

- Users can log in using an email or phone number to recieve a verification code. 
- For email login, the Twilio SendGrid Email API is used to send the code.
- For phone login, the Twilio Messaging Service is used to send the code. 
- Upon succesful verification, Iron Session stores encrypted sessiond ata in cookies. 
- This encrypted session data can only be decrypted on the server side. 
  <br /><br />
  <img height="700" src="./2.gif" />

> 2. 프로필

- Users can view and edit their profile photo, name, email, and phone number.
- Tabs like Neighborhood Life and Favorites allow users to view their posts or favorite items.
- Tabs for Selling and Sold let users view active and completed listings.
- Users can view or leave reviews and ratings through the Review tab.
  <br /><br />
  <img height="700" src="./3.gif" />

> 3. 상품 및 포스트 검색

- Users can search products by name.
- Users can search posts by content.
  <br /><br />
  <img height="700" src="./4.gif" />

> 4. 상품

- View all items listed in the secondhand marketplace.
- Load more products with the "See more" option.
- Click on a product to view detailed information.
- Upload a product with image, name, price, and description.
- Images are optimized and stored using Cloudflare Images.
  <br /><br />
  <img height="700" src="./5.gif" />

> 5. 상품 상세정보

- View images, name, price, description, and like count.
- Like a product to add it to favorites using SWR to update the cache.
- Click "Chat with Seller" to initiate a conversation.
- Sellers can mark items as sold.
- Related products with similar names are displayed.
  <br /><br />
  <img height="700" src="./6.gif" />

> 6. 포스트

- View all community posts under "Neighborhood Life".
- Load more posts with "See more".
- Click on a post to view detailed content.
- Create posts by uploading images and writing descriptions.
- Images are optimized and stored using Cloudflare Images.
  <br /><br />
  <img height="700" src="./7.gif" />

> 7. 포스트 상세정보

- View image, description, comment count, and likes.
- Like a post to add it to favorites and update cache via SWR.
- Add and delete comments.
  <br /><br />
  <img height="700" src="./8.gif" />

> 8. 스트리밍

- View all streaming sessions.
- Click to view details of a stream.
- Create a stream by entering title and content.
  <br /><br />
  <img height="700" src="./9.gif" />

> 9. 스트리밍 상세정보

- Watch live or latest streams on the stream details page.
- Streamers can start live streams using server URL and stream key from Cloudflare Stream.
- Live stream pages show current viewers and allow real-time chat.
- After ending, recorded videos are saved and available as latest streams.
  <br /><br />
  <img height="700" src="./10.gif" />

> 10. 채팅

- View all chat rooms.
- Click on a chat to view details.
  <br /><br />
  <img height="700" src="./11.gif" />

> 11. 채팅 상세정보

- Chat directly with the product seller.
- After completing a transaction, users can leave the chat room.
  <br /><br />
  <img height="700" src="./12.gif" />

## Pages

> Root

- 홈
- 로그인
- 검색

> User

- 동네 생활
- 관심 목록
- 판매 물품
- 판매 완료
- 거래 후기
- 프로필 수정

> Product

- 전체 상품
- 상품 상세정보

> Post

- 전체 포스트
- 포스트 상세정보

> Stream

- 전체 스트리밍
- 스트리밍 상세정보

> Chat

- 전체 채팅
- 채팅 상세정보

## Features

### 🙎‍♂️ User

- [x] 이메일, 휴대폰 로그인
- [x] 로그아웃
- [x] 프로필 보기
- [x] 아바타 업로드
- [x] 프로필 수정
- [x] 리뷰 작성
- [x] 리뷰 삭제

### 📦 Product

- [x] 전체 상품 보기
- [x] 상품 상세정보 보기
- [x] 상품 업로드
- [x] 상품 삭제
- [x] 상품 좋아요
- [x] 상품 검색
- [x] 상품 판매완료
- [x] 상품 판매자와 채팅

### 📋 Post

- [x] 전체 포스트 보기
- [x] 포스트 상세정보 보기
- [x] 포스트 작성
- [x] 포스트 삭제
- [x] 포스트 좋아요
- [x] 포스트 검색
- [x] 포스트 댓글

### 🎥 Stream

- [x] 전체 스트리밍 보기
- [x] 스트리밍 상세정보 보기
- [x] 스트리밍 생성
- [x] 스트리밍 삭제
- [x] 스트리밍 채팅

### 💬 Chat

- [x] 전체 채팅 보기
- [x] 채팅 상세정보 보기
- [x] 채팅 생성
- [x] 채팅 삭제

## License

<a>MIT</a>
