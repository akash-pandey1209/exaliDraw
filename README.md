## 🏗️ Tech Stack  

**Frontend**  
- Next.js  
- React  
- Tailwind CSS  

**Backend**  
- Node.js  
- Express.js  
- WebSockets  

**Database**  
- PostgreSQL  
- Prisma ORM  

**DevOps & Tooling**  
- Turborepo – monorepo management  
- PNPM – fast package installs  
- TypeScript – type safety  

---

## 📂 Monorepo Structure  

exaliDraw/
├── apps/
│ ├── excelidraw-frontend # Next.js frontend
│ ├── http-backend # REST API backend
│ ├── ws-backend # WebSocket backend
│ └── web # Playground / demo app
├── packages/
│ ├── db # Prisma schema + migrations
│ ├── ui # Shared UI components
│ ├── common # Shared utilities
│ └── typescript-config # Central TS configs




---

## 🚀 Getting Started  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/exalidraw-clone.git
cd exalidraw-clone



2️⃣ Install dependencies
pnpm install

3️⃣ Setup environment variables

Create a .env file in the root:

DATABASE_URL="postgresql://user:password@localhost:5432/exalidraw"

4️⃣ Run database migrations
pnpm prisma migrate dev
pnpm prisma generate

5️⃣ Start development
pnpm run dev


## 📸 Screenshots

### Whiteboard View  
![Excalidraw Screenshot 1](./assets/EXACLIDRAW1.jpg)

### Collaboration View  
![Excalidraw Screenshot 2](./assets/exaclidraw2.jpg)
