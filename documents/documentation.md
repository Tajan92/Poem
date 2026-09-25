# Documenting a REST API


| Method | URL             | Request Body (JSON) | Response (JSON) | Error (e) |
|--------|-----------------|----------------------|------------------|-----------|
| GET    | /api/users      |                      | [user, user, …] (1) |         |
| GET    | /api/users/{id} |                      | user (1)         | (e1)      |
| POST   | /api/users      | user(1) without id   |                  | (e2)      |
| UPDATE | /api/users/{id} | user(1) without id   | user (1)         |           |