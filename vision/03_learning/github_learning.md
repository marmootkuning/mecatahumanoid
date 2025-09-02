## GITHUB

# GitHub Learning Notes
## Date: 1 September 2025

### Core Concepts Mastered Today

#### 1. Repository Management
- **Personal Repository**: Full control over project
- **Repository Creation**: GitHub → New repository → Fill details → Create
- **Repository URL Format**: `https://github.com/username/repo-name.git`

#### 2. Git Remote Configuration
```bash
# Check current remote
git remote -v

# Remove existing remote
git remote remove origin

# Add new remote
git remote add origin https://github.com/username/repo-name.git

# Verify remote configuration
git remote -v

Platform kolaborasi kode berbasis web yang menggunakan Git (sistem kontrol versi).

# [Fungsi utama:]
Menyimpan proyek kode (repository).
Melacak perubahan kode (version control).
Kolaborasi tim (pull request, issue, dll).
Hosting website (GitHub Pages).

# Istilah
- Repository
Folder proyek yang menyimpan semua file kode + riwayat perubahan.
- Commit
"Snapshot" perubahan kode (dengan pesan deskripsi).
- Branch
Salinan independen kode untuk pengembangan fitur baru (misal: main, dev).
- Push
Mengunggah perubahan lokal ke GitHub.
- Pull
Mengunduh perubahan terbaru dari GitHub ke lokal.
- Clone
Mengunduh repository GitHub ke komputer lokal.
- Pull Request (PR)
Permintaan untuk menggabungkan perubahan dari satu branch ke branch lain (biasanya ke main)

# Initialize repository (if new)
git init

# Add files to staging area
git add .

# Commit changes
git commit -m "Clear commit message"

# Push to remote repository
git push -u origin master

# Check status
git status
4. Repository Migration Process
Create new repository on GitHub
Update local remote URL
Push all files to new repository
Verify all files are present
5. Troubleshooting Common Issues
Issue: "Repository not found"
Cause: Incorrect repository URL or repository doesn't exist
Solution:

# Check current remote
git remote -v

# Update to correct URL
git remote set-url origin https://github.com/correct-username/correct-repo.git