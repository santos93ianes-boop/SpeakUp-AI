# SpeakUp AI v2

Aplicativo Android para aprender inglês de forma leve, com foco em conversação e prática diária.

## O que já funciona sem API
- Conversação guiada por texto.
- Entrada por voz usando o reconhecimento do Android.
- Leitura das respostas em inglês (Text-to-Speech).
- Níveis A1, A2, B1, B2, C1 e C2.
- Modos: conversa livre, viagem, trabalho, restaurante e entrevista.
- Correções leves de erros comuns.
- Botão “Me ajude a responder”.
- Tradução opcional para iniciantes.
- Aulas rápidas e frases essenciais com áudio.
- Teste de nivelamento.
- XP, progresso por habilidade e conquistas.
- Botão que abre o WhatsApp com uma mensagem de prática pronta.

## Importante sobre IA real
A versão do APK funciona de forma local e guiada, sem exigir chave de API. Para a professora responder livremente a qualquer assunto como uma IA generativa, conecte o aplicativo a um backend seguro. Não coloque a chave secreta diretamente no APK ou no repositório público.

## Gerar o APK no GitHub
1. Crie um repositório e envie o conteúdo deste projeto para a raiz dele.
2. Abra **Actions** no GitHub.
3. Escolha **Build Android APK**.
4. Clique em **Run workflow**.
5. Ao final, abra a execução e baixe o artefato `SpeakUpAI-debug-apk`.

O workflow também roda automaticamente quando houver push para `main` ou `master`.


## V4 — Seleção de idioma na abertura
- Tela inicial premium para escolher English ou Español antes de entrar no curso.
- Progresso e experiência continuam separados por idioma.
- Alternância entre inglês e espanhol permanece disponível dentro do app.
