# 보안 스타트업에서 Django 사용하는 방법

## 악성코드 분석 창업 멤버
- 기존에 Flask 사용
- 추가 개발 요청이 많을 예정
- 문서, 테스트, URI 등이 존재하지 않았음

## 새로운 시스템을 만들자
- 검색기능 추가
- 관리자 사이트 추가
- 분석 요청 기능
- 장고 : Admin Page, inspectdb, User, Documentation

## 관리자페이지
- 기존 : VPN으로 DB접근
- inspectdb를 사용해 테이블 마이그레이션

## 분석요청 기능
- Celery, Redis 사용
- URL을 받고 해당 사이트를 분석한다.
- 기존의 원시적인 방법을 자동화시키도록 개선을 했다.

## Caching
