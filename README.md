<p align="center">
  <img src="./png/background.png" alt="Banner" width="100%">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains%20Mono&weight=500&size=18&pause=1400&color=8B949E&center=true&vCenter=true&width=780&height=50&lines=Android+system-level+engineering;ADB+%2F+Shizuku%2C+sem+root;Performance+mensur%C3%A1vel%2C+n%C3%A3o+placebo" alt="Typing SVG" />
</p>

<h1 align="center">Keven · KevenModz</h1>

<p align="center">
  <strong>System Performance Researcher</strong><br>
  <sub>Android Internals · Vendor Research · Magisk · AxManager</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Magisk-00AF9C?style=flat-square&logo=magisk&logoColor=white" />
</p>

<p align="center">
  <a href="#sobre">Sobre</a> ·
  <a href="#coredroid">CoreDroid</a> ·
  <a href="#pesquisa">Pesquisa</a> ·
  <a href="#projetos">Projetos</a>
</p>

---

## Sobre

Comecei em otimização por necessidade: meu aparelho tinha que rodar melhor e ninguém tinha a resposta. Hoje estudo como cada fabricante limita CPU, térmica e renderização.

Pesquiso o que fica escondido, meço de verdade e transformo em ajuste que funciona com ou sem root.

- **Device:** Poco X5 Pro (778G / Adreno 642L)
- **Foco:** MIUI / HyperOS, One UI, Motorola
- **Método:** Props via ADB + Shizuku, sem root + App e módulos Magisk / AxManager

---

## CoreDroid — v1.7 Stable

> 2 anos de desenvolvimento · App Android com 40+ ajustes via Shizuku, sem root. Performance, renderização, bateria e sistema numa única interface.

<details>
<summary><b>Ver lista completa de recursos</b></summary>
<br>

**Segurança e sistema:** Trava de Segurança (anti-reversão do Play Services), Core Repair, Partitions Trimmer, Core Shell
**Monitoramento:** Dashboard completo (SoC, GPU, RAM, bateria, kernel, uptime)
**Performance:** Core Mode, Turbo Sched, PerfMagic, Supressão térmica
**Renderização:** Render Preload (System, ANGLE, Native, Game Driver por app), Vulkan / OpenGL, SkiaVK / SkiaGL
**Tela e input:** Desbloqueador de FPS, anti burn-in, otimização de UI/launcher, touch e input lag
**Memória:** Limpeza, compressão de RAM, ZRAM/swap, ART / Dex2oat
**Outros:** Bateria (cache freeze, carga rápida), Rede (ping), Áudio (Surround, Hi-Fi), Core IA e Core Utils

> Aviso: recursos que removem limites térmicos exigem monitoramento.

</details>

### Complemento WebUI + Perfis por Fabricante

<details>
<summary><b>Ver detalhes da WebUI e Core Brands</b></summary>
<br>

**WebUI:** Criei uma ponte própria entre WebUI e Shizuku pra rodar comandos ADB direto pelo site do app. Módulos: Driver Booster (SurfaceFlinger), Performance Fixa, Alta Prioridade, Limpador ART, Desativar Conexões Google.

**Xiaomi Optimizer:** Performance Mode, cache, animações flagship, Game Turbo, vídeo e HDR
**Samsung Optimizer:** Top App, remoção de telemetria e limites de FPS (recursos de S21 Ultra+)
**Motorola Optimizer:** Parâmetros topo de linha, toque e CPU/GPU

</details>

---

## Pesquisa por Fabricante

- **Xiaomi / HyperOS:** Props `ro.*` / `persist.sys.*` via ADB sem root, blur e texturas em low-RAM, remoção de limitação de CPU, thermal
- **Samsung:** Modo Top App que limpa memória em uso pesado
- **Motorola:** Recursos extraídos de ROM topo de linha (áudio, toque, performance)

---

## Outros Projetos

**Módulos Magisk:** Zenith Next (gráficos/CPU/rede) e ZRAM Focus (RAM/swap/armazenamento)
**AxManager (sem root):** Estabilidade de FPS, bateria e RAM

**Packs e Ferramentas:**
- **Windows Pack:** Pack completo pra Windows, sistema, jogos e input (mouse/teclado). Média +40 FPS sem forçar PC no talo
- **Linux Pack:** Kernel, memória, energia, bateria e sistema com backup
- **ApkRushTool:** Ferramenta Python pra modding de APK
- **OPT-X / Newb X Dawn LITE:** Texture pack e shader focado em FPS sem perder gráfico

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,androidstudio,bash,linux,git,vscode,py,c" />
</p>

---

## Como usar

1. Ativa Shizuku e concede ADB
2. Instala o CoreDroid (APK das Releases)
3. Aplica o perfil do teu fabricante e segue as instruções do app

## Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KevenDev7z&show_icons=true&theme=tokyonight&hide_border=true" height="150" />
  <img src="https://streak-stats.demolab.com?user=KevenDev7z&theme=tokyonight&hide_border=true" height="150" />
</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/KevenDev7z/KevenDev7z/output/pacman-contribution-graph-dark.svg">
</p>

---

## Contato

<p align="left">
  <a href="mailto:kevenfreire514@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://github.com/KevenDev7z">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:30363d&height=100&section=footer" width="100%" />
</p>
