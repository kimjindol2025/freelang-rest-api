# 🔗 FreeLang REST API Framework

[![Language](https://img.shields.io/badge/language-Rust-orange.svg)](#)
[![Status](https://img.shields.io/badge/status-Production%20Ready-brightgreen.svg)](#)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-kimjindol2025%2Ffreelang--rest--api-blue?logo=github)](https://github.com/kimjindol2025/freelang-rest-api)

**RESTful API 개발을 위한 완전한 프레임워크**

## 📋 특징

- ✅ Route 자동 등록
- ✅ JSON 직렬화
- ✅ 요청 검증
- ✅ 에러 처리
- ✅ CORS 지원

## 🎯 빠른 예제

```freeLang
#[get("/users/{id}")]
fn get_user(id: i64) -> Result<User, Error> {
  Ok(User { id, name: "Alice" })
}

#[post("/users")]
fn create_user(body: CreateUserRequest) -> Result<User, Error> {
  // Implementation
}
```

## 🔧 빌드

```bash
cargo build --release
```

## 라이선스

MIT License © 2026

---

**버전**: 1.8.0 | **업데이트**: 2026-03-16 | **상태**: 🟢 프로덕션
