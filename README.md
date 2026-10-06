# Portfólio — Guilherme Thomas

Site pessoal com foco em **redes e cloud**, feito em uma única página HTML com tema de terminal. Reúne formação, habilidades, certificações e contatos.

🔗 **Site:** https://guithomas.com.br

## Sobre

- Graduado em Sistemas de Informação pela UNINOVE (São Paulo, SP)
- Certificado AWS Certified Cloud Practitioner
- Concluiu o CCNAv7: Introdução às Redes (Cisco Networking Academy)
- Em preparação para CCNA 200-301 e AWS Solutions Architect Associate (SAA-C03)
- Busca oportunidades em suporte cloud, redes e cibersegurança

## Tecnologias

- HTML e CSS puros, sem frameworks e sem etapa de build
- Tema claro e escuro automático, conforme o sistema do visitante
- Layout responsivo para celular e desktop
- Hospedagem gratuita no GitHub Pages, com domínio próprio

## Estrutura

```
.
├── index.html   # página única (conteúdo, estilos e layout)
├── CNAME        # domínio personalizado (guithomas.com.br)
└── README.md
```

## Rodar localmente

Não há dependências. Basta abrir o arquivo no navegador:

```bash
git clone https://github.com/SEU-USUARIO/portfolio.git
cd portfolio
xdg-open index.html   # Linux (no macOS use "open", no Windows "start")
```

Ou servir com um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Publicação (GitHub Pages + domínio próprio)

1. Em **Settings → Pages**, selecione *Deploy from a branch*, branch `main`, pasta `/ (root)`.
2. Em **Custom domain**, informe `guithomas.com.br` (isso mantém o arquivo `CNAME` no repositório).
3. No Registro.br, em **DNS → Editar zona**, crie:
   - quatro registros **A** no domínio raiz: `185.199.108.153`, `185.199.109.153`, `185.199.110.153` e `185.199.111.153`
   - um registro **CNAME** para `www` apontando para `SEU-USUARIO.github.io`
4. Depois que o DNS propagar, ative **Enforce HTTPS**.

## Como atualizar o conteúdo

Edite o `index.html` e faça commit na branch `main`. O GitHub Pages republica o site automaticamente em poucos minutos.

## Contato

- LinkedIn: https://linkedin.com/in/guithomasbr
- E-mail: guithomasbr@gmail.com
- WhatsApp: https://wa.me/5511961113965

