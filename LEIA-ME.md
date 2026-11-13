# Coleta e consulta de frases — INDIGENISTA 1.0

Aplicativo de página única para coletar e consultar frases de atendimento em línguas indígenas, a partir de frases de partida em português, espanhol e francês. Versão 0.2.0, 14/11/2026. **Candidata em desenvolvimento, não homologada.**

- `index.html`: o aplicativo. Funciona no navegador, também sem internet depois da primeira visita.
- `demonstracao.html`: a mesma página em modo demonstração, com exportações desligadas. Para conhecer o aplicativo sem registrar pessoas reais.

## Proteção dos dados

- O que as pessoas registram fica **somente no aparelho**, cifrado (AES-256-GCM).
- A página é proibida de enviar dados pela internet. Este servidor só entrega o código do aplicativo e nunca recebe dados.
- O cofre tem **três guardiões**. Dois juntos abrem; um sozinho não abre. Cada guardião tem uma senha e um código de recuperação impresso.
- Cópias de segurança são cifradas e podem ser restauradas em outro aparelho com dois guardiões.
- O cofre se fecha sozinho após 10 minutos sem uso. Não existe chave mestra.

## Uso real

Coleta com pessoas e comunidades indígenas só depois da consulta prévia, livre e informada e das autorizações formais. Sem autorização registrada, o aplicativo funciona em modo de teste.

O banco tem 10.462 frases de partida. 272 foram propostas e revisadas para o banco v1; as demais são rascunhos combinatórios a revisar. Nenhuma tradução em língua indígena foi produzida por máquina.

A fonte Rawline está sob a licença SIL Open Font License (`OFL_Rawline.txt`).
