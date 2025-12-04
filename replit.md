# LDFisioterapia - Landing Page

## Visão Geral
Landing page moderna e profissional para LDFisioterapia, empresa de fisioterapia especializada comandada pela fisioterapeuta Larissa Dias (CREFITO-04 408036-F).

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript (Vanilla)
- Python 3.11 (servidor web)

## Estrutura do Projeto
```
/
├── index.html          # Página principal
├── style.css           # Estilos CSS
├── script.js           # Interatividade JavaScript
├── server.py           # Servidor web Python
├── favicon.svg         # Favicon moderno SVG
├── sitemap.xml         # Mapa do site para SEO
├── robots.txt          # Diretivas para crawlers
├── replit.md           # Documentação do projeto
└── .gitignore          # Arquivos ignorados pelo Git
```

## Características da Landing Page

### Seções Implementadas
1. **Header Fixo** - Logo, menu de navegação e botão CTA "Agendar Agora"
2. **Hero Section** - Headline impactante com ilustração e CTA para WhatsApp
3. **Sobre a Profissional** - Apresentação de Larissa Dias com registro profissional
4. **Especialidades** - 4 cards destacando os serviços:
   - Fisioterapia Domiciliar
   - Eletroterapia
   - Laserterapia
   - Pilates Solo
5. **Benefícios do Tratamento** - 6 benefícios principais
6. **Atendimento Domiciliar** - Destaque para atendimento em casa
7. **Depoimentos** - 3 depoimentos fictícios (editáveis)
8. **CTA Final** - Chamada para ação destacada
9. **Rodapé** - Contatos e redes sociais
10. **Botão Flutuante WhatsApp** - Acesso rápido ao WhatsApp

### Design e Estética
- **Paleta de Cores**: Turquesa (#4ECDC4), Verde-claro, Branco
- **Tipografia**: Poppins (Google Fonts)
- **Estilo**: Clean, acolhedor e profissional
- **Responsividade**: Mobile-first, totalmente responsivo para todas as telas (480px a 1900px+)

### Funcionalidades
- Menu hambúrguer para dispositivos móveis
- Navegação suave (smooth scroll)
- Animações ao scrollar
- Header que adapta ao scroll
- Botão flutuante de WhatsApp com animação
- Favicon moderno com gradiente

### Contatos Integrados
- **WhatsApp**: (34) 9 9909-1134
- **Instagram**: @ldfisioterapia
- **Link WhatsApp**: https://wa.me/5534999091134

## SEO Implementado

### Meta Tags
- Title otimizado com palavras-chave
- Description com até 160 caracteres
- Keywords relevantes para fisioterapia
- Canonical URL
- Robots meta tag (index, follow)
- Author e language tags

### Open Graph (Facebook)
- og:type, og:url, og:title, og:description
- og:image, og:locale, og:site_name

### Twitter Cards
- twitter:card (summary_large_image)
- twitter:url, twitter:title, twitter:description, twitter:image

### Geo Tags
- geo.region (BR-MG)
- geo.placename (Uberlândia)

### Schema.org (JSON-LD)
- HealthAndBeautyBusiness com informações completas
- Serviços listados (Fisioterapia Domiciliar, Eletroterapia, Laserterapia, Pilates)
- Dados de contato, localização e horário
- WebSite schema com SearchAction
- BreadcrumbList para navegação

### Arquivos de SEO
- **sitemap.xml**: Mapa do site para indexação
- **robots.txt**: Diretivas para crawlers com link do sitemap

### Acessibilidade
- Aria-labels em links e botões
- Role attributes em elementos interativos
- Estrutura semântica (header, main, footer)
- Alt text em imagens/SVGs

## Como Executar
O servidor está configurado para rodar automaticamente:
```bash
python server.py
```
Acesse em: http://localhost:5000

## Última Atualização
04 de Dezembro de 2025
