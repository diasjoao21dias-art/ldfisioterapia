# 🏥 LDFisioterapia - Landing Page Profissional

Landing page moderna, responsiva e otimizada para a empresa de fisioterapia LDFisioterapia.

## 📋 Informações do Projeto

**Profissional**: Larissa Dias  
**Registro**: CREFITO-04 408036-F  
**Contato WhatsApp**: (34) 9 9909-1134  
**Instagram**: @ldfisioterapia

## 🎨 Características

✅ Design moderno e profissional  
✅ Totalmente responsivo (mobile-first)  
✅ Cores clean e acolhedoras (azul, verde-claro, branco)  
✅ SEO básico implementado  
✅ Animações suaves ao scrollar  
✅ Botão flutuante de WhatsApp  
✅ Menu hambúrguer para mobile  
✅ Navegação suave entre seções

## 🚀 Como Usar

O servidor está configurado e rodando automaticamente. Basta acessar a URL fornecida pelo Replit.

Para rodar manualmente:
```bash
python server.py
```

## ✏️ Como Personalizar

### 1. Editar Depoimentos

Abra o arquivo `index.html` e localize a seção `<section id="depoimentos">`. Você encontrará 3 depoimentos como este:

```html
<div class="depoimento-card">
    <div class="aspas">"</div>
    <p class="texto">SEU DEPOIMENTO AQUI</p>
    <div class="autor">
        <div class="autor-avatar">INICIAIS</div>
        <div class="autor-info">
            <p class="nome">NOME DO CLIENTE</p>
            <p class="tratamento">TIPO DE TRATAMENTO</p>
        </div>
    </div>
</div>
```

Edite o texto, nome e iniciais conforme necessário.

### 2. Adicionar Novas Especialidades

Na seção `<section id="especialidades">`, adicione um novo card:

```html
<div class="card">
    <div class="card-icon">
        <!-- Seu ícone SVG aqui -->
    </div>
    <h3>Nome da Especialidade</h3>
    <p>Descrição da especialidade</p>
</div>
```

### 3. Alterar Cores

No arquivo `style.css`, modifique as variáveis CSS no início:

```css
:root {
    --primary-color: #4ECDC4;        /* Cor principal */
    --primary-dark: #2D7A74;         /* Cor escura */
    --secondary-color: #45B7AF;      /* Cor secundária */
    --accent-color: #E8F5F3;         /* Cor de destaque */
    --text-dark: #2C3E50;            /* Texto escuro */
    --text-light: #6C7A89;           /* Texto claro */
}
```

### 4. Modificar Textos

Todos os textos estão no arquivo `index.html`. Procure pela seção desejada e edite diretamente.

### 5. Adicionar Fotos Reais

Substitua os placeholders SVG por imagens reais:

**Exemplo - Hero Section:**
```html
<!-- Substituir -->
<div class="hero-image-placeholder">...</div>

<!-- Por -->
<img src="caminho/para/sua-imagem.jpg" alt="Fisioterapia profissional">
```

**Exemplo - Sobre:**
```html
<!-- Substituir -->
<div class="sobre-image-circle"></div>

<!-- Por -->
<div class="sobre-image-circle" style="background-image: url('foto-larissa.jpg'); background-size: cover; background-position: center;"></div>
```

## 📱 Estrutura das Seções

1. **Header** - Logo, menu e botão CTA
2. **Hero** - Chamada principal com WhatsApp
3. **Sobre** - Informações da profissional
4. **Especialidades** - 4 cards de serviços
5. **Benefícios** - 6 benefícios do tratamento
6. **Atendimento Domiciliar** - Destaque para atendimento em casa
7. **Depoimentos** - 3 casos de sucesso
8. **CTA Final** - Chamada para agendamento
9. **Rodapé** - Contatos e redes sociais

## 🔗 Links Importantes

Todos os botões "Agendar" e o botão flutuante direcionam para:
```
https://wa.me/5534999091134
```

O link do Instagram é:
```
https://www.instagram.com/ldfisioterapia
```

## 📦 Arquivos do Projeto

- `index.html` - Estrutura da página
- `style.css` - Estilos e design
- `script.js` - Interatividade
- `server.py` - Servidor web
- `.gitignore` - Arquivos ignorados

## 🎯 Próximos Passos Sugeridos

- [ ] Adicionar fotos reais da profissional e do ambiente de trabalho
- [ ] Inserir depoimentos reais de pacientes
- [ ] Adicionar mais especialidades conforme necessário
- [ ] Incluir galeria de fotos (opcional)
- [ ] Configurar domínio personalizado
- [ ] Adicionar Google Analytics (opcional)

## 💡 Dicas

- Para alterar o número do WhatsApp, busque por `5534999091134` em todos os arquivos
- As cores seguem o padrão de clínica premium (clean e acolhedor)
- Todas as animações são suaves e discretas
- O site é otimizado para carregar rapidamente

## 📞 Suporte

Para dúvidas sobre personalização, consulte a documentação HTML/CSS ou entre em contato.

---

**Desenvolvido com ❤️ para LDFisioterapia**
