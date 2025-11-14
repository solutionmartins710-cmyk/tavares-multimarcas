
TAVARES MULTIMARCAS - ZIP pronto para deploy no Netlify com Netlify CMS (git-gateway)
Arquivos importantes:
- index.html  (loja pública)
- /admin/index.html  (Netlify CMS entry)
- /admin/config.yml (config do CMS - backend: git-gateway)
- /content/products/*.md (conteúdo inicial)
- /data/products.json (arquivo que o front-end consome)

Instruções rápidas de deploy:
1) Crie um repositório no GitHub (ex: 'tavares-multimarcas') e faça push dos arquivos deste ZIP.
2) No Netlify: Add new site -> Import from Git -> conecte com o repositório -> deploy.
3) No painel do site no Netlify: Site settings -> Identity -> Enable Identity.
4) Ainda em Identity: Service settings -> Enable Git Gateway -> authorize Git provider (GitHub).
5) Em Identity > Invite users, adicione o seu e-mail (solutionmartins710@gmail.com) como 'editor' OU faça login via GitHub em /admin (o Netlify pode pedir para você confirmar).
6) Acesse https://<seu-site>.netlify.app/admin e faça login. Você poderá editar/adiicionar produtos e imagens. As mudanças serão commitadas no repo conectado e o site será atualizado.

Se quiser eu te envio passo-a-passo com prints para cada um desses passos.
