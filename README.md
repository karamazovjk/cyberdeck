# Klaus 2.0 — Cyberdeck

> Um laboratório portátil construído a partir de hardware descartado, doações e peças ociosas — com foco em acesso à informação, inclusão digital e redução de e-waste.

---
### Colaboradores

- **Jackson** — [@karamazovjk](https://github.com/karamazovjk)
- **Ana Beatriz** — [@usuario](https://github.com/usuario)

### Status

🟡 Em construção — hardware sendo montado, software em planejamento.

---

## O que é

Klaus 2.0 é um cyberdeck de uso geral construído com princípios de reaproveitamento eletrônico. O projeto une hardware de descarte com software livre para criar uma estação de trabalho portátil e autossuficiente — funcional sem conexão com a internet, acessível a qualquer dispositivo na mesma rede local.

O projeto era, inicialmente, um estudo pessoal de hardware e funcionamento eletrônico; porém há a intenção em transforma-lo em uma pesquisa academica, ou até mesmo uma iniciação científica na **UFABC**, com foco nas interseções entre e-waste, acesso à informação e tecnologia acessível; visto que os envolvidos são estudantes de Ciência de Dados e Ciência da Computação, respectivamente.

---

## Contexto acadêmico


- Como hardware descartado pode ser reaproveitado como infraestrutura de acesso à informação?
- Quais são as barreiras práticas e potenciais de soluções offline para inclusão digital?
- De que forma projetos de e-waste reaproveitado se relacionam com princípios de tecnologia acessível?

> Publicações e relatórios serão adicionados conforme o projeto avança.

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

### Biblioteca offline
- **Wikipedia em português** (completa, com imagens) via [Kiwix](https://kiwix.org)
- **Project Gutenberg** — acervo de livros em domínio público
- Servido localmente via `kiwix-serve`, acessível por qualquer dispositivo na rede

### Rádio SDR
- Recepção de rádio via módulo **RTL-SDR** (USB)
- Software: [SDR++](https://github.com/AlexandreRouma/SDRPlusPlus) ou [GQRX](https://gqrx.dk/)
- Antena acoplável externamente

### Laboratório de programação
- Python, C, e ambiente de desenvolvimento leve
- Editor de código: [VSCodium](https://vscodium.com/) ou [Lite XL](https://lite-xl.com/)
- Notebooks Jupyter para ciência de dados

### Utilitários gerais
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
### observações:

Como parte da iniciativa, todo o processo e componentes utilizados serão documentados, de forma a facilitar a compreensão e disponibilização desses dados, dessa forma, qualquer pessoa interessada em reproduzir ou adaptar o projeto terá total liberdade para tal.

---
