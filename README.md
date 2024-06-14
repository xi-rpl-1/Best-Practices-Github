# Remote

## Menambahkan Remote Baru

1. **Tambahkan Remote Baru**:
   ```bash
   git remote add <remote_name> <remote_url>
   ```
   contoh:
   ![alt text](assets/image.png)
2. **Verifikasi Remote atau Cek Remote**:
   ```bash
   git remote -v
   ```

## Mengubah URL Remote

1. **Mengubah URL**:
   ```bash
   git remote set-url <remote_name> <new_remote_url>
   ```
   contoh:
   ![alt text](assets/image-1.png)

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

## Mengambil Perubahan dari Remote

1. **Pull dari Remote**:
   ```bash
   git pull origin main
   ```
