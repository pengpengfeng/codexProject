# Architect Constraints

## 技术栈锁定
- Frontend: Vue 3 + TypeScript + Pinia + SCSS/CSS Variables
- Backend: Python 3.12+ + FastAPI + Pydantic v2 + SQLAlchemy 2.x (async)
- Database: PostgreSQL 16
- Cache/Queue: Redis

## 禁用依赖
- 未经审批的 UI 组件库
- 未经审批的 ORM 替代框架

## 部署限制
- 必须支持容器化部署（Docker）
- 所有配置通过环境变量注入
- 日志输出 JSON 结构，便于集中采集
