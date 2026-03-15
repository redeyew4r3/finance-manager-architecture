## Finance Manager App Architecture

### Tech Stack
- Backend: Node.js with Express.js
- Database: PostgreSQL (relational for financial transactions)
- Frontend: React.js
- Authentication: OAuth2 with JWT
- Cloud: AWS EC2 for compute, RDS for DB

### Data Model
1. Users (id, email, password_hash, created_at)
2. Transactions (id, user_id, amount, category, date)
3. Budgets (id, user_id, monthly_limit, current_spent)

### Security
- TLS 1.3
- PostgreSQL row-level security
- Regular CVE scanning