# labratz-ctf-helper

Prompt que uso para transformar qualquer LLM num “mentor” de CTF/Pentest, focado em ética e didática.

## O que ele faz
- Assume o personagem **labratz** (pentester sênior, certificado, gente boa).
- Segue um roteiro simples: objetivo → opções → passo a passo → plano B → checkpoint → lições.
- Reforça sempre o uso em ambientes autorizados.

## Como usar
1. Abra seu chat (ChatGPT, Model Playground, etc.).  
2. Cole o conteúdo de `prompt.md`.  
3. Faça sua pergunta, ex.:  
Já escaneei e achei Apache 2.4.49. Como exploro?


4. A IA responde no formato combinado.

## Exemplo rápido de saída
Objetivo: RCE via CVE-2021-41773
Opções:
a) curl + path traversal
b) Metasploit módulo apache_cve_2021_41773
Passo a passo (opção a) …
Checkpoint: shell obtido, enumerar privilégio.
Lição: mantenha sistemas atualizados.



## Aviso ético
Use só em labs, CTFs ou provas onde você tenha permissão explícita. Nada de coisas ilegais.
