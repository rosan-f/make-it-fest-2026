# 🌿 Git Workflow

## Branching Strategy

Kami menggunakan strategi branching berikut:

```
main
├── develop
│   ├── feature/nama-fitur
│   ├── fix/nama-bug
│   └── chore/nama-task
```

## Branch

| Branch | Kegunaan |
|--------|----------|
| `main` | Branch produksi, selalu stabil |
| `develop` | Branch pengembangan utama |
| `feature/*` | Pengembangan fitur baru |
| `fix/*` | Perbaikan bug |
| `chore/*` | Task non-fungsional (config, docs, dll) |

## Konvensi Penamaan Branch

```
feature/nama-fitur-singkat
fix/nama-bug-singkat
chore/nama-task
```

**Contoh:**
- `feature/user-authentication`
- `fix/login-error`
- `chore/update-dependencies`

## Konvensi Commit Message

Gunakan format [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<scope>): <description>
```

**Tipe:**
| Tipe | Kegunaan |
|------|----------|
| `feat` | Fitur baru |
| `fix` | Perbaikan bug |
| `docs` | Perubahan dokumentasi |
| `style` | Formatting, bukan logika |
| `refactor` | Refactoring kode |
| `test` | Menambah atau memperbaiki test |
| `chore` | Update tools, config, dll |

**Contoh:**
```
feat(auth): add user login functionality
fix(api): resolve 500 error on user endpoint
docs(readme): update installation guide
```

## Alur Pengerjaan

1. `git checkout develop`
2. `git pull origin develop`
3. `git checkout -b feature/nama-fitur`
4. Kerjakan fitur, commit secara berkala
5. `git push origin feature/nama-fitur`
6. Buat Pull Request ke `develop`
7. Review & merge

## Pull Request

- Beri judul yang deskriptif
- Sertakan deskripsi singkat perubahan
- Tambahkan screenshot jika ada perubahan UI
- Minta review dari minimal 1 anggota tim sebelum merge
