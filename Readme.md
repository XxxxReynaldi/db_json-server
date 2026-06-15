## Running JSON Server

Masuk ke folder yang berisi file `db.json`:

```bash
cd db
```

Jalankan JSON Server:

```bash
npx json-server --watch db.json --port 3000
```

Jika belum pernah menginstall JSON Server:

```bash
npm install -g json-server
```

Kemudian jalankan:

```bash
json-server --watch db.json --port 3000
```

Mock API akan tersedia di:

```text
http://localhost:3000
```

---

## Project Structure

```text
project-root/
├── src/
├── db/
│   └── db.json
├── package.json
└── README.md
```

---

## Build for Production

```bash
npm run build
```

Hasil build akan tersedia pada folder:

```text
dist/
```
