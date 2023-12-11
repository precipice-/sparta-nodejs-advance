# 환경변수

.env 파일 생성 후 아래 내용 추가

## 설명

- SERVER_PORT: 서버 포트 번호
- DATABASE_URL: Prisma 연결용 Database 주소
- PASSWORD_HASH_SALT_ROUNDS: bcrypt salt 보안 강도 (숫자가 높으면 보안은 강화되지만 시간이 오래 걸림)
- JWT_ACCESS_TOKEN_SECRET: JWT AccessToken 비밀번호

## 예시

```bash
SERVER_PORT=3000
DATABASE_URL="mysql://root:rootpassword@aaa.ap-northeast-2.rds.amazonaws.com:3306/nodejs-advance"
PASSWORD_HASH_SALT_ROUNDS=10
JWT_ACCESS_TOKEN_SECRET="jwt-select-key"
```

# 실행 방법

```bash
npm install
npm run dev
```

# API 명세서 URL

https://docs.google.com/spreadsheets/d/1-_HMdxZOUkmOLYcTqN8UHypJoMVHqESIze3s_gbDywo/edit?usp=sharing

# ERD URL

https://www.erdcloud.com/d/zzo9JoKE9Z7zfHTwq
