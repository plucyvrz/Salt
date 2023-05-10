<h1 align="center">Stable Diffusion WebUI</h1>

###
<center>
<img src="https://i.ibb.co/jvjr7gZ/Capture.png">
</center>

# Run in Colab
<center><a href="https://colab.research.google.com/github/plucyvrz/WebUI/blob/master/StableDiffusionUI.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
<h2> Dibutuhkan minimal Colab Pro tier ($9.99 / month) agar tidak ke banned dari google colab
</center>

# Instruksi

<a href="https://i.ibb.co/r5ZcSV2/image.png"><img src="https://i.ibb.co/r5ZcSV2/image.png" alt="image" border="0"></a>
1. Periksa username dan password untuk menggunakan WebUI.

2. Ceklis model dan extension yang ingin di gunakan, jika ingin menggunakan <a href="#files-tambahan-yang-saya-gunakan">files</a> saya, disana terdapat 40 lebih models yang tersedia

| **Models** |      **Extension**     |
|:----------:|:----------------------:|
|     v1     |       TagComplete      |
|     v2     |        ControlNet      |
|    Anime   |       ImageBrowser     |
|     Art    |        darkTheme       |
|  Realistic |       InfiniteZoom     |
|            |         DeForum        |
|            |          AddNet        |
|            |      CivitAIBrowser    |
|            |       RatioHelper      |
|            |   Ultimate_SD_Upscale  |
|            |     Openpose_Editor    |
|            |     Prompt_Enhancer    |

3. Klik tombol play untuk run colab (Colab free 5-6 Menit untuk pertama kali run, dan 2 menit untuk re-run jika terjadi kesalahan/crash).
4. Klik link `gradio.live` atau  `ngrok.io` di log untuk lanjut menggunakan AUTOMATIC1111.

# ngrok (Optional)
Gunakan [ngrok](https://ngrok.com/) jika mengalami tombol yang kurang responsif setelah generate gambar.
  1. Buka https://ngrok.com/
  2. Daftar akun
  3. Verifikasi Email
  4. Copy auth token dari https://dashboard.ngrok.com/get-started/your-authtoken dan pastekan di column ngrok token di colab.

# File(s) tambahan yang saya gunakan
Checkpoint : [Google Drive](https://drive.google.com/drive/folders/1-4VZiM8MH-cre_9ClV6-nChsgu-1xnfW?usp=share_link)

Lora Models : [Google Drive](https://drive.google.com/drive/folders/1-J3PuhCGITdE3lYwAQCCCZBxGkpuGb4q?usp=share_link)

Upscaler : [Google Drive](https://drive.google.com/drive/folders/1-IsJh63QLKYKD5zGyDp6ybbi9Gso1MbL?usp=share_link)

Embeddings : [Google Drive](https://drive.google.com/drive/folders/1-_u4cSFqClRpv58p_PF28p_sRknGCzar?usp=share_link)

# Cara memasang files agar bisa digunakan
Untuk menggunakan semua files yang diatas, bisa menggunakan cara ini.
Setelah run pertama kali, masuk ke folder `output_path` dan hapus folder berikut
  1. `models`
  2. `Lora`
  3. `ESRGAN`
  4. `embeddings`
  
Setelah itu, buat pintasan drive dari folder google drive saya ke `output_path` kalian
<br>
<details>
  <summary> MyDrive/output_path/ </summary>
    <img src="https://i.ibb.co/y6frwWh/3.png">
   </summary>
</details>
<br>

Setelah itu kalian bisa jalankan ulang dan hasilnya seperti ini
<br>
<details>
  <summary>Loaded Files</summary>
  <img src="https://i.ibb.co/D1FN00j/4.png">
  </summary>
</details>
<br>

# Credits:
- SergioDev
- You

# Me
Jika ada pertanyaan atau copyright material hubungi [saya](mailto:plucyvrz@gmail.com)
