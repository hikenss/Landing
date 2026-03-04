# Deploy Vercel — Checklist Rápido

## 1) Publicar
- Entre na pasta `vercel_landing`.
- Rode:

```bash
npx vercel --prod
```

## 2) Configurar domínio
- No projeto Vercel, abra **Settings → Domains**.
- Adicione o domínio principal.
- Configure DNS conforme instruções da Vercel.

## 3) Verificar rotas obrigatórias
- `/`
- `/artigo-1/`
- `/artigo-2/`
- `/comunidade/`
- `/sobre/`
- `/contato/`
- `/politica-de-privacidade/`
- `/termos-de-uso/`

## 4) Validar CTA e tracking
- Acesse `/comunidade/` com UTMs de teste.
- Clique no botão de comunidade.
- Confirmar redirecionamento para Telegram com `start=` preenchido.
- Confirmar chegada de `utm_*`, `fbp` e `fbc` no backend.

## 5) Aquecimento do domínio (recomendado)
- Criar propriedade no Google Search Console.
- Solicitar indexação da home e dos dois artigos.
- Esperar pelo menos 1 URL indexada antes de escalar tráfego.

## 6) Regras de mídia/anúncio
- Linguagem neutra (confiança, relacionamento, evolução pessoal).
- Sem promessas absolutas.
- Sem termos explícitos no criativo e na página.

## 7) Escala operacional
- Iniciar com orçamento baixo.
- Manter 3–5 dias sem alterações grandes.
- Escalar em incrementos graduais.
- Duplicar anúncio ao ajustar, sem editar aprovado.
