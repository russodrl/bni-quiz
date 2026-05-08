# 🚀 Como Hospedar o Quiz no Hostinger

## Opção 1 — File Manager (mais rápido, 2 minutos)

1. Vai a **hpanel.hostinger.com** → Inicia sessão
2. No menu lateral, clica em **Ficheiros** → **File Manager**
3. Navega até à pasta do teu domínio (geralmente `public_html/`)
4. Cria uma pasta nova: `bni-quiz`
5. Entra na pasta `bni-quiz`
6. Clica em **Upload** → seleciona os 2 ficheiros:
   - `index.html` (o quiz)
   - `roteiro.html` (o roteiro)
7. Pronto! Acede a: `https://oteudominio.com/bni-quiz/`

## Opção 2 — Se quiseres na raiz do domínio

1. Mesmos passos, mas upload direto para `public_html/`
2. Acede a: `https://oteudominio.com/`

## ⚠️ Notas

- O QR code do quiz aponta para a URL onde está a ser acedido
- Se usares um subdomínio (ex: `quiz.oteudominio.com`), o QR vai apontar para esse subdomínio
- Testa no telemóvel antes da apresentação
- O quiz funciona 100% offline (sem dependências externas exceto o QR code que usa CDN)

## 📁 Ficheiros para upload

Estão em: `/opt/data/home/bni-quiz/`
- `index.html` — Quiz interativo (12 perguntas + QR code)
- `roteiro.html` — Roteiro da apresentação (5 min)
