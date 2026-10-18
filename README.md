<p align="center">
  <img src="./assets/background.png" alt="Banner" width="100%">
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains%20Mono&weight=500&size=18&pause=1400&color=8B949E&center=true&vCenter=true&width=780&height=50&lines=Android+system-level+engineering;Privilege+escalation+via+ADB+%2F+Shizuku%2C+sem+root;Performance+mensur%C3%A1vel%2C+n%C3%A3o+placebo" alt="Typing SVG" />
</p>

<h1 align="center">Keven <sub>· KevenModz</sub></h1>

<p align="center">
  <b>System Performance Researcher</b><br>
  <sub>Android Internals · Vendor Research · Magisk · AxManager</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Magisk-00AF9C?style=flat-square&logo=magisk&logoColor=white" />
  <img src="https://img.shields.io/badge/Brasil-181717?style=flat-square" />
</p>

<p align="center">
  <a href="#sobre">Sobre</a> ·
  <a href="#coredroid">CoreDroid</a> ·
  <a href="#pesquisa-por-fabricante">Pesquisa</a> ·
  <a href="#outros-projetos">Projetos</a> ·
  <a href="#stack">Stack</a> ·
  <a href="#contato">Contato</a>
</p>

---

## Sobre

Comecei em otimização de Android por necessidade: precisava que meu aparelho rodasse melhor e ninguém tinha a resposta pronta. Hoje passo horas estudando como cada fabricante implementa governors, térmica, renderização e gerenciamento de memória, e faço isso porque gosto de entender o sistema por dentro.

Meu método é encontrar o que fica limitado ou escondido, validar com medição e transformar em ajuste aplicável, com ou sem root.

- Pesquisa ativa em **MIUI / HyperOS**, **One UI** e **Motorola**
- Execução de props de sistema via **ADB**, sem root
- Desenvolvimento de app, módulos Magisk e módulos AxManager
- Dispositivo de referência: **Poco X5 Pro**, Snapdragon 778G, Adreno 642L

---

## CoreDroid

> Mais de 2 anos de desenvolvimento contínuo · **v1.7 Stable**

App Android de otimização que opera com privilégios elevados via **Shizuku** (ADB), sem exigir root. Reúne ajustes por fabricante, reparo de sistema e monitoramento em uma única interface.

| Módulo | Função |
|---|---|
| **Core Brands** | Perfis dedicados: Xiaomi Optimizer, Samsung Optimizer e Motorola Optimizer |
| **Trava de Segurança** | Protege o banco de dados de configurações para que o Google Play Services e atualizações em segundo plano não revertam as otimizações |
| **Core Repair** | Reparo de sistema, touch e sensores |
| **Core Info / Dashboard** | Telemetria em tempo real: SoC, GPU, CPU, taxa de atualização, bateria, RAM e armazenamento |
| **Complemento de Injeção** | Módulos isolados e ativáveis individualmente: Driver Booster (camada SurfaceFlinger), Performance Fixa (governors de frequência) e prioridade alta de processos |

<details>
<summary><b>Perfis por fabricante</b></summary>

<br>

**Xiaomi Optimizer**
Habilita Performance Mode, otimiza cache de apps, ativa animações de topo de linha, libera recursos adicionais no sistema e no Game Turbo, e melhora qualidade de vídeo e HDR.

**Samsung Optimizer**
Otimiza processos e parâmetros de CPU, remove restrições de desempenho, desativa telemetria geral, adiciona otimizações presentes apenas em aparelhos topo de linha (a partir do S21 Ultra) e remove limitações de taxa de quadros.

**Motorola Optimizer**
Aplica parâmetros de alto desempenho de aparelhos topo de linha, extraídos de ROM e do sistema de um Moto G15.

</details>

---

## Pesquisa por fabricante

| Fabricante | Resultados |
|---|---|
| **Xiaomi / HyperOS** | Props `ro.*`, `persist.sys.*` e comuns via ADB, sem root · Blur e texturas avançadas em aparelhos low-RAM · Remoção de limitação de CPU · Thermal menos restritivo |
| **Samsung / One UI** | Ativação do modo **Top App**, que limpa memória periodicamente durante uso de apps pesados |
| **Motorola** | Recursos ocultos extraídos de ROM de aparelho topo de linha: melhorias de áudio, toque e performance |

---

## Outros projetos

**Módulos Magisk**

| Módulo | Escopo |
|---|---|
| **Zenith Next** | Gráficos, CPU e rede |
| **ZRAM Focus** | RAM, ZRAM, swap e armazenamento |

**Módulos AxManager (sem root)**
Estabilidade de FPS, gestão de bateria e RAM, e armazenamento otimizado para carregamento de texturas.

**Ferramentas e packs**

| Projeto | Descrição |
|---|---|
| **ApkRushTool** | Ferramenta em Python para modding de APK, com otimização para Minecraft |
| **KNBoost OPT-X Ultimate** | Texture pack Bedrock focado em FPS |
| **Newb X Dawn LITE (otimizado)** | Shader reduzido para aparelhos intermediários |
| **Windows Pack** | Debloat, planos de energia, jogos, mouse e teclado |
| **Linux Pack** | Kernel, memória, energia e bateria, com backup |

> Links dos repositórios: adicionar em cada projeto.

---

## Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=kotlin,androidstudio,py,bash,c,linux,windows,git,vscode" />
  </a>
</p>

---

## Atividade

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=midnightshady&show_icons=true&theme=city_lights&hide_border=true&border_radius=5" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=midnightshady&layout=compact&theme=city_lights&hide_border=true&border_radius=5" height="150" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=midnightshady&theme=city_lights&hide_border=true&border_radius=5" height="150" />
</div>

<p align="center">
  <img src="https://raw.githubusercontent.com/midnightshady/midnightshady/output/pacman-contribution-graph-dark.svg">
</p>

---

## Contato

<p align="left">
  <a href="mailto:kevenfreire514@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <!-- Preencha a URL e descomente:
  <a href="https://www.linkedin.com/in/SEU-USUARIO" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  -->
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:30363d&height=100&section=footer" width="100%" />
</p>
