# StudyGroup-MP-Motionlab

## Rangkuman Materi Version Control & Git

### 1. Apa itu Version Control?

Version Control adalah sistem yang digunakan untuk mengelola dan melacak perubahan pada kode atau dokumen. Dengan version control, kita bisa:

- Menyimpan versi-versi perubahan.
- Kembali ke versi sebelumnya jika terjadi kesalahan.
- Berkolaborasi dalam tim dengan lebih mudah.

### 2. Git

Git adalah salah satu sistem Version Control yang paling populer dan digunakan luas oleh developer. Fungsinya antara lain:

- Mencatat perubahan kode.
- Memungkinkan kerja tim melalui branch.
- Menyimpan riwayat commit sehingga bisa rollback.

### 3. GitHub

GitHub adalah platform berbasis web yang menggunakan Git untuk:

- Menyimpan repository secara online.
Berkolaborasi dalam tim.
- Memanfaatkan fitur seperti pull request, issue tracker, code review, dan project board.
- Alternatif lainnya: GitLab (dengan CI/CD), Bitbucket (integrasi dengan Atlassian).

### 4. Fitur utama Git
| Fitur            | Fungsi Singkat                                        |
| ---------------- | ----------------------------------------------------- |
| **Commit**       | Menyimpan snapshot perubahan.                         |
| **Branching**    | Membuat cabang kode untuk fitur atau eksperimen baru. |
| **Merging**      | Menggabungkan branch ke branch lain.                  |
| **Revert/Reset** | Mengembalikan perubahan ke commit tertentu.           |
| **Stash**        | Menyimpan perubahan sementara tanpa commit.           |

### 5. Workflow Git
| Workflow                    | Penjelasan                                                                                                      |
| --------------------------- | --------------------------------------------------------------------------------------------------------------- |
| **Centralized Workflow**    | Semua bekerja pada satu branch utama (main/master).                                                             |
| **Feature Branch Workflow** | Setiap fitur dibuat di branch terpisah lalu digabungkan.                                                        |
| **Gitflow**                 | Struktur branch lengkap: main, develop, feature, release, hotfix (untuk development, testing, hingga produksi). |


### 6. Perintah Git Dasar

| Perintah                   | Fungsi                                   |
| -------------------------- | ---------------------------------------- |
| `git init`                 | Membuat repository baru.                 |
| `git status`               | Melihat status perubahan file.           |
| `git add <file>`           | Menambahkan file ke staging area.        |
| `git commit -m "message"`  | Menyimpan perubahan.                     |
| `git push origin <branch>` | Mengirim commit ke GitHub.               |
| `git pull`                 | Mengambil perubahan terbaru dari GitHub. |
| `git checkout -b <branch>` | Membuat sekaligus pindah branch.         |
| `git checkout <branch>`    | Pindah ke branch lain.                   |
| `git reset --hard <hash>`  | Kembali ke commit tertentu.              |
| `git log`                  | Melihat riwayat commit.                  |

### 7. Konflik dan Kolaborasi di GitHub

- Conflict terjadi ketika dua orang mengubah bagian kode yang sama. Harus diselesaikan manual.
- Fork: Menyalin repository orang lain ke akun kita.
- Pull Request (PR): Permintaan untuk menggabungkan perubahan dari branch/repo lain ke branch utama.
- Code Review: Proses pengecekan kode sebelum merge untuk menjaga kualitas.
