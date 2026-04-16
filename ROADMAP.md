# Roadmap — Klaus 2.0 Cyberdeck

Este documento descreve as fases planejadas do projeto, do hardware bruto até uma plataforma funcional de pesquisa e acesso à informação.

> 🟡 Status atual: **Fase 1 em andamento**

---

## Fase 1 — Fundação de Hardware
*Montar a base física do projeto*

- [x] Definir componentes disponíveis e listar origens (e-waste, doações, ociosos)
- [x] Adquirir carcaça (caixa de ferramentas adaptada)
- [x] Teclado disponível
- [x] HD externo 500GB disponível
- [ ] Receber Raspberry Pi 4
- [ ] Definir solução de tela
- [ ] Montar carcaça física com os componentes

---

## Fase 2 — Sistema Operacional e Configuração Base
*Deixar o Pi funcional e configurado*

- [ ] Instalar Arch Linux ARM (Alarm) no Raspberry Pi 4
- [ ] Configurar acesso SSH
- [ ] Montar e configurar HD externo (ext4)
- [ ] Configurar hotspot local (para acesso de outros dispositivos via WiFi)
- [ ] Testar acesso pelo PSP e outros dispositivos

---

## Fase 3 — Biblioteca Offline
*O núcleo de acesso à informação do projeto*

- [ ] Instalar e configurar `kiwix-serve`
- [ ] Baixar Wikipedia em português (completa, com imagens)
- [ ] Baixar Project Gutenberg
- [ ] Testar acesso pelo browser do PSP e dispositivos móveis
- [ ] Organizar estrutura de arquivos no HD (`/zim`, `/livros`, etc.)

---

## Fase 4 — Laboratório de Programação
*Transformar o Klaus em ambiente de desenvolvimento portátil*

- [ ] Instalar Python + pip + Jupyter
- [ ] Instalar editor de código leve (VSCodium ou Lite XL)
- [ ] Instalar compilador C/C++
- [ ] Testar fluxo de desenvolvimento local completo

---

## Fase 5 — Rádio SDR *(experimental)*
*Recepção de rádio via hardware acoplável*

- [ ] Adquirir módulo RTL-SDR
- [ ] Adquirir/construir antena acoplável
- [ ] Instalar e configurar SDR++ ou GQRX
- [ ] Documentar frequências e uso

---

## Fase 6 — Pesquisa e Documentação Acadêmica
*Formalizar o projeto como iniciação científica*

- [ ] Definir orientador(a) na UFABC
- [ ] Formular questão de pesquisa formal
- [ ] Levantar referências bibliográficas (`research.md`)
- [ ] Produzir primeiro relatório de progresso
- [ ] Submeter para edital de IC

---

## Ideias futuras *(sem prazo definido)*

- Utilitários offline: calculadora científica, bloco de notas, mapas (OpenStreetMap via Kiwix)
- Servidor de mídia local (músicas, filmes, podcasts baixados)
- Documentação em vídeo do processo de montagem
- Apresentação do projeto em evento acadêmico

---

*Última atualização: Abril 2026*
