# MyProject Fullstack

全栈项目初始化完成，采用前后端分离架构：

- Frontend: Vue 3 + TypeScript + Vite
- Backend: FastAPI + Pydantic v2
- Infra: Docker Compose（本地开发）

## 目录结构

```text
MyProject/
├── frontend/
├── backend/
└── docker-compose.yml
```

## 快速开始

### 1) 启动后端

```bash
cd MyProject/backend
python -m venv .venv
source .venv/bin/activate
pip install -e .
uvicorn app.main:app --reload --port 8000
```

### 2) 启动前端

```bash
cd MyProject/frontend
npm install
npm run dev
```

### 3) Docker 启动（可选）

```bash
cd MyProject
docker compose up --build
```
