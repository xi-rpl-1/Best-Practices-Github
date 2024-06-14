# Menghubungkan Repository Lokal dengan Remote

1. **Inisialisasi Repository Lokal**:
   ```bash
   git init
   ```
   ![alt text](image-2.png)
2. **Tambahkan Remote**:
   ```bash
   git remote add origin https://github.com/username/repository.git
   ```
   ![alt text](assets/image.png)

# Remote

## Menambahkan Remote Baru

1. **Tambahkan Remote Baru**:
   ```bash
   git remote add <remote_name> <remote_url>
   ```
   contoh:
   ![alt text](assets/image.png)
2. **Verifikasi Remote**:
   ```bash
   git remote -v
   ```
   ![alt text](image-6.png)

## Mengubah URL Remote

1. **Mengubah URL**:
   ```bash
   git remote set-url <remote_name> <new_remote_url>
   ```
   contoh:
   ![alt text](assets/image-1.png)

# Push

## Mengirim Perubahan ke Remote

1. **Cek Perubahan**:
   ```bash
   git status
   ```
   ![alt text](image.png)
2. **Staging Perubahan**:
   ```bash
   git add .
   ```
   ![alt text](image-1.png)
3. **Commit Perubahan**:

   ```bash
   git commit -m "Deskripsi perubahan"
   ```

   ![alt text](image-3.png)

4. **Push ke Remote**:
   ```bash
   git push origin main
   ```
   ![alt text](image-4.png)

# Pull

## Mengambil Perubahan dari Remote

1. **Pull dari Remote**:
   ```bash
   git pull origin main
   ```
   ![alt text](image-5.png)
