# Menghubungkan Repository Lokal dengan Remote

1. **Inisialisasi Repository Lokal**:
   ```bash
   git init
   ```
2. **Tambahkan Remote**:
   ```bash
   git remote add origin https://github.com/username/repository.git
   ```

# Remote

## Menambahkan Remote Baru

1. **Tambahkan Remote Baru**:
   ```bash
   git remote add <remote_name> <remote_url>
   ```
2. **Verifikasi Remote**:
   ```bash
   git remote -v
   ```

## Mengubah URL Remote (Changing Remote URL)

1. **Mengubah URL**:
   ```bash
   git remote set-url <remote_name> <new_remote_url>
   ```

# Push

## Mengirim Perubahan ke Remote

1. **Staging Perubahan**:
   ```bash
   git add .
   ```
2. **Commit Perubahan**:
   ```bash
   git commit -m "Deskripsi perubahan"
   ```
3. **Push ke Remote**:
   ```bash
   git push origin main
   ```

# Pull

## Mengambil Perubahan dari Remote (Pulling Changes from Remote)

1. **Pull dari Remote**:
   ```bash
   git pull origin main
   ```
