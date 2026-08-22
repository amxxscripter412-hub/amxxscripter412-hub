Template GitHub Profile README (Cyber / Dev / Gaming Aesthetic)
Berikut adalah template lengkap file README.md beserta konfigurasinya untuk membuat profil GitHub kamu terlihat super keren dengan animasi typing, ASCII header, 3D contribution graph, Spotify integration, serta Snake Game action.
1. File README.md (Salin Seluruh Isinya ke Repository Profile Kamu)
<!-- ======================================================== -->
<!-- ASCII HEADER & ANIMATED TYPING BANNER -->
<!-- ======================================================== -->
<div align="center">

<pre>
 ██████╗ ██████╗ ██████╗ ███████╗    ██████╗ ███████╗██╗   ██╗
██╔════╝██╔═══██╗██╔══██╗██╔════╝    ██╔══██╗██╔════╝██║   ██║
██║     ██║   ██║██║  ██║█████╗      ██║  ██║█████╗  ██║   ██║
██║     ██║   ██║██║  ██║██╔══╝      ██║  ██║██╔══╝  ╚██╗ ██╔╝
╚██████╗╚██████╔╝██████╔╝███████╗    ██████╔╝███████╗ ╚████╔╝ 
 ╚═════╝ ╚═════╝ ╚═════╝ ╚══════╝    ╚═════╝ ╚══════╝  ╚═══╝  
</pre>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00FF66&center=true&vcenter=true&width=600&lines=Game+Server+Developer+%26+Scripter;Python+%26+Automation+Specialist;Building+Custom+Systems+%26+Tools;CS+1.6+%7C+ReAPI+%7C+AMX+Mod+X;Always+Exploring+New+Tech..." alt="Typing SVG" />
</a>

<p>
  <img src="https://img.shields.io/badge/Status-Building%20Cool%20Stuff-00FF66?style=for-the-badge&logo=github&logoColor=black" />
  <img src="https://img.shields.io/badge/Focus-Server%20Architecture-blue?style=for-the-badge&logo=codefactor&logoColor=white" />
  <img src="https://img.shields.io/badge/Vibe-Phonk%20%26%20Synthpop-purple?style=for-the-badge&logo=spotify&logoColor=white" />
</p>

</div>

---

<!-- ======================================================== -->
<!-- ABOUT ME & TECH STACK -->
<!-- ======================================================== -->
<h2>⚡ About Me & Tech Arsenal</h2>

```yaml
Developer:
  Role: Game Server Developer & Automation Scripter
  Core Tech: Python, PAWN (AMXX / ReAPI), C++, Web Tech
  Interests: System Architecture, Bot Automation, Custom Scripts
  Vibe: Quiet mind, loud code, late-night debugging
```

### 🛠️ Languages & Tools

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white" />
  <img src="https://img.shields.io/badge/Sublime%20Text-FF9800?style=for-the-badge&logo=sublimetext&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

<!-- ======================================================== -->
<!-- ANIMATED SNAKE GAME & 3D GRAPH -->
<!-- ======================================================== -->
<h2>🎮 Contribution Snake Game & 3D World</h2>

<div align="center">

<p>Ular ini memakan kontribusi komit GitHub secara otomatis setiap harinya!</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/amxxscripter412-hub/amxxscripter412-hub/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/amxxscripter412-hub/amxxscripter412-hub/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/amxxscripter412-hub/amxxscripter412-hub/output/github-contribution-grid-snake.svg">
</picture>

<br/><br/>

### 🌐 3D Isometric View
<img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="GitHub 3D Contribution Graph" width="100%" />

</div>

---

<!-- ======================================================== -->
<!-- GITHUB STATS & SPOTIFY -->
<!-- ======================================================== -->
<h2>📊 GitHub Metrics & Live Status</h2>

<div align="center">

<table border="0">
  <tr>
    <td width="50%" align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=amxxscripter412-hub&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
    </td>
    <td width="50%" align="center">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=amxxscripter412-hub&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" />
    </td>
  </tr>
</table>

<br/>

<!-- Live Spotify Card (Opsional) -->
<a href="https://spotify.com">
  <img src="https://novathena-spotify-now-playing.vercel.app/api/spotify" alt="Spotify Now Playing" width="400" />
</a>

</div>

---

<div align="center">
  <p>"Code is like humor. When you have to explain it, it’s bad."</p>
  <img src="https://komarev.com/ghpvc/?username=amxxscripter412-hub&color=00FF66&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views" />
</div>
2. Panduan Pengaturan GitHub Actions (Untuk Animasi Ular & Graph 3D)
Agar animasi ular (Snake Game) dan grafik 3D berjalan otomatis, buat dua file workflow di dalam repository profil kamu:
A. Workflow Animasi Ular (Snake Game)
Buat file baru di path: .github/workflows/snake.yml lalu isi dengan kode berikut:
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *" # Jalan otomatis tiap jam 12 malam
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push Snake SVG to Output Branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
B. Workflow Grafik 3D (3D Isometric Graph)
Buat file baru di path: .github/workflows/models3d.yml lalu isi dengan kode berikut:
name: Generate 3D Contribution Graph

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: yoshi38610/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.repository_owner }}
      - name: Commit & Push
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add -A .
          git commit -m "Update 3D Contribution Graph" || exit 0
          git push
3. Langkah Terakhir (Penting!)
Ganti semua teks amxxscripter412-hub pada file README.md dengan username GitHub kamu.
Buka tab Actions di repository kamu dan jalankan workflow secara manual sekali (Run workflow) agar gambar SVG awal terbentuk.
Pastikan di menu Settings > Actions > General, opsi Workflow permissions diatur ke Read and write permissions.
