## How to set up

```bash
npm install
```

```sql
CREATE DATABASE tasks (
    id SERIAL PRIMARY KEY,
    title VARCHAR NOT NULL,
    is_done BOOLEAN DEFAULT FALSE,
    created_at TIMESTAMP DEFAULT now(),
    modified_at TIMESTAMP
);
```

## How to develop

```bash
npm dev
```