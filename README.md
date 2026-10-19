<p align="center">
  <img src="./background.png" alt="Banner" width="100%">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains%20Mono&weight=500&size=18&pause=1400&color=8B949E&center=true&vCenter=true&width=780&height=50&lines=Android+system-level+engineering;Root+%26+Non-Root+Solutions;Performance+mensur%C3%A1vel%2C+n%C3%A3o+placebo" alt="Typing SVG" />
</p>

<h1 align="center">Keven · Engenheiro de software</h1>

<p align="center">
  <strong>System Performance Researcher</strong><br>
  <sub>Android Internals · Vendor Research · Magisk · AxManager · PC Optimization</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Magisk-00AF9C?style=flat-square&logo=magisk&logoColor=white" />
</p>

<p align="center">
  <a href="#sobre">Sobre</a> ·
  <a href="#coredroid">CoreDroid</a> ·
  <a href="#pesquisa">Pesquisa</a> ·
  <a href="#pc">PC Packs</a> ·
  <a href="#minecraft">Minecraft</a>
</p>

---

## Sobre

Comecei em otimização por necessidade: meu aparelho tinha que rodar melhor e ninguém tinha a resposta. Hoje estudo como cada fabricante cria sistemas internos, funções e muito mais.

Pesquiso o que fica escondido, meço de verdade e transformo em ajuste que funciona com ou sem root.

- **Device:** Poco X5 Pro (778G / Adreno 642L)
- **Foco:** MIUI / HyperOS, One UI, Motorola
- **Método:** Props via ADB + Shizuku, sem root + App e módulos Magisk / AxManager

---

## CoreDroid — v1.7 Stable

> 2 anos de desenvolvimento · App Android com 40+ ajustes via Shizuku, sem root. Performance, renderização, bateria e sistema numa única interface.

<p align="center">
  <img src="./coredroid1.jpg" width="48%" />
  <img src="./coredroid2.jpg" width="48%" />
</p>

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

<details>
<summary><b>Complemento WebUI + Perfis por Fabricante</b></summary>
<br>

**WebUI:** Ponte própria entre WebUI e Shizuku pra rodar ADB direto no app. Módulos: Driver Booster (SurfaceFlinger), Performance Fixa, Alta Prioridade, Limpador ART, Desativar Conexões Google.

**Xiaomi:** Performance Mode, cache, animações flagship, Game Turbo, vídeo e HDR
**Samsung:** Top App, remoção de telemetria e limites de FPS (recursos de S21 Ultra+)
**Motorola:** Parâmetros topo de linha, toque e CPU/GPU

</details>

---

## Pesquisa por Fabricante

- **Xiaomi / HyperOS:** Props `ro.*` / `persist.sys.*` via ADB sem root, blur e texturas em low-RAM, remoção de limitação de CPU, thermal
- **Samsung:** Modo Top App que limpa memória em uso pesado
- **Motorola:** Recursos extraídos de ROM topo de linha (áudio, toque, performance)

---

## Packs de PC

### Windows Pack - Completo
Pack extremamente completo que cobre tudo que um Windows precisa pra ter performance real. Sistema, jogos, rede, serviços e periféricos. Inclui otimização de mouse e teclado pra latência e resposta. Ganho médio de +40 FPS, podendo pegar mais dependendo do hardware, sem forçar PC no talo. Sem booster fake que só fecha processo.

### Linux Pack
Pack focado em performance desktop. Otimização de kernel (Liquorix), gerenciamento de memória, energia, bateria e sistema. Backup e limpeza do sistema, TLP, Swappiness, ZRAM, Preload e prevenção de erros.

---

## Minecraft

### KNBoost OPT-X Ultimate
Texture pack Bedrock focado em ganho de FPS. Mantém qualidade gráfica e chunks, sem deixar o jogo feio. FPS a mais com visual limpo.

### Newb X Dawn LITE (Otimizado)
Shader ultra otimizado e elegante pra aparelho intermediário. Versão que otimizei pra rodar liso em hardware fraco/médio, mantendo sombra e iluminação bonita sem pesar.

### KN-CraftTools
Ferramenta em Python pra modding de apks, com foco em otimização pra Minecraft Bedrock.

---

## Outros

### Módulos Magisk

#### Zenith Next (gráficos / CPU / rede)

<p align="center">
  <img src="./zenith1.jpg" width="32%" /><img src="./zenith2.jpg" width="32%" /><img src="./zenith3.jpg" width="32%" />
</p>
<p align="center">
  <img src="./zenith4.jpg" width="32%" /><img src="./zenith5.jpg" width="32%" />
</p>

#### ZRAM Focus Next (RAM / swap / armazenamento)

Focado em ZRAM, swap e limpeza de armazenamento pra manter RAM livre em uso pesado e jogos. Otimiza compressão e gerenciamento de memória.

<p align="center">
  <img src="./zram-focus.jpg" alt="ZRAM-Focus Next Relatório" width="100%">
</p>

### AxManager (sem root)
Frames, bateria, ram e armazenamento otimizados para extrair o máximo do dispositivo. Plugins específicos para Samsung e Xiaomi.

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,androidstudio,bash,linux,windows,git,vscode,py,c" />
</p>

---

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
