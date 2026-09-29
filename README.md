# Pinho Konvertilo — Releases

Repositório público de distribuição do **Pinho Konvertilo** para Android.

Este repositório é um **mirror binário de releases**. Ele existe para publicar APKs assinados, checksums, notas de versão e links oficiais do projeto. **O código-fonte do aplicativo não é distribuído aqui.**

## Versão atual

- **Versão:** 0.1.21
- **Build / versionCode:** 22
- **Package:** `com.pinhotedio.converter`
- **Android mínimo:** Android 7.0 / API 24
- **Modelo:** local-first / processamento no aparelho

## Integridade da release R1

APK canônico assinado:

```text
SHA-256:
0a1343ec06835536c93e86aab56f78be3dd8879f127ee09969b4c92684688872

Certificado SHA-256:
9ed1b163f60500a192c4083c2ff4fa760fee64322795eee187470e2c18270458
```

Sempre confira o checksum antes de instalar um APK obtido fora de uma loja.

## Sobre o Pinho Konvertilo

O Pinho Konvertilo é um conversor de arquivos **local-first** para Android. O app analisa o conteúdo do arquivo no próprio aparelho e só oferece rotas de conversão suportadas pelas engines realmente disponíveis na build atual.

Recursos incluem:

- conversão local de arquivos;
- detecção do conteúdo físico observado;
- OCR on-device;
- PinhoLab para inspeção de arquivos;
- histórico local;
- escolha do destino dos resultados;
- temas claro, escuro e sistema.

## Privacidade

Conversões e inspeções são projetadas para permanecer no aparelho.

Política de privacidade oficial:
https://github.com/sasandralean-prog/PinhoKonvertiloPrivacy

O apoio opcional ao projeto abre externamente na Stripe. O Pinho Konvertilo não recebe nem armazena dados de cartão.

## Downloads

Os binários públicos serão disponibilizados em **GitHub Releases** deste repositório.

Cada release deve conter, no mínimo:

- APK assinado;
- arquivo SHA-256;
- notas da versão.

## Estrutura deste mirror

```text
README.md
CHANGELOG.md
SHA256SUMS.txt
releases/
└── 0.1.21/
    └── release-notes.md
```

## Segurança

O APK oficial deve ser assinado pelo certificado cujo SHA-256 é:

`9ed1b163f60500a192c4083c2ff4fa760fee64322795eee187470e2c18270458`

Um APK com assinatura diferente **não deve ser tratado como release oficial do Pinho Konvertilo**.

---

**Pinho Konvertilo** · conversão e inspeção locais para Android.
