# Klaus 2.0 — Cyberdeck

> Um laboratório portátil construído a partir de hardware descartado, doações e peças ociosas — com foco em acesso à informação, inclusão digital e redução de e-waste.

---

## O que é

Klaus 2.0 é um cyberdeck de uso geral construído com princípios de reaproveitamento eletrônico. O projeto une hardware de descarte com software livre para criar uma estação de trabalho portátil e autossuficiente — funcional sem conexão com a internet, acessível a qualquer dispositivo na mesma rede local.

O projeto é desenvolvido como iniciação científica na **UFABC**, com foco nas interseções entre e-waste, acesso à informação e tecnologia acessível.

---

## Hardware

| Componente | Origem |
|---|---|
| Raspberry Pi 4 | Aquisição nova |
| HD externo 500GB | Ociosa / reutilizado |
| Teclado | Doação |
| Carcaça (caixa de ferramentas) | Reutilizada |
| Peças diversas | Descarte eletrônico (UFABC + outras fontes) |

> 📋 Lista completa de componentes e origem em [`/hardware/inventory.md`](./hardware/inventory.md)

---

## Funcionalidades planejadas

### ✅ Biblioteca offline
- **Wikipedia em português** (completa, com imagens) via [Kiwix](https://kiwix.org)
- **Project Gutenberg** — acervo de livros em domínio público
- Servido localmente via `kiwix-serve`, acessível por qualquer dispositivo na rede

### 📻 Rádio SDR
- Recepção de rádio via módulo **RTL-SDR** (USB)
- Software: [SDR++](https://github.com/AlexandreRouma/SDRPlusPlus) ou [GQRX](https://gqrx.dk/)
- Antena acoplável externamente

### 💻 Laboratório de programação
- Python, C, e ambiente de desenvolvimento leve
- Editor de código: [VSCodium](https://vscodium.com/) ou [Lite XL](https://lite-xl.com/)
- Notebooks Jupyter para ciência de dados

### 📝 Utilitários gerais
- Bloco de notas / anotações offline
- Calculadora científica
- Ferramentas de terminal

---

## Software base

- **OS:** Arch Linux ARM (Alarm)
- **Servidor de conteúdo:** kiwix-serve
- **Acesso remoto:** SSH / hotspot local

---

## Estrutura do HD (planejada)

```
/media/hd-externo/
├── zim/
│   ├── wikipedia_pt_all_maxi.zim
│   └── gutenberg.zim
├── livros/
├── projetos/
└── backups/
```

---

## Contexto acadêmico

Este projeto está sendo desenvolvido como pesquisa de iniciação científica na UFABC. As questões centrais que guiam o trabalho:

- Como hardware descartado pode ser reaproveitado como infraestrutura de acesso à informação?
- Quais são as barreiras práticas e potenciais de soluções offline para inclusão digital?
- De que forma projetos de e-waste reaproveitado se relacionam com princípios de tecnologia acessível?

> Publicações e relatórios serão adicionados conforme o projeto avança.

---

## Autoras

- **Jackson** — [@karamazovjk](https://github.com/karamazovjk)
- **[nome da amiga]** — [@usuario](https://github.com/usuario)

UFABC — Bacharelado em Ciências e Tecnologia  
Ênfases: Ciência de Dados / Neurociência

---

## Status

🟡 Em construção — hardware sendo montado, software em planejamento.
