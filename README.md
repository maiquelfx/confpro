# Conf PRO - Portal de Conferências de Computação

## 📋 O que foi desenvolvido

Um portal moderno e responsivo com:
- ✨ **Rastro brilhante do mouse** - Efeito visual elegante que segue o cursor
- 🔍 **Busca em tempo real** - Filtre conferências por sigla, nome ou palavras-chave
- 📊 **Filtros avançados** - Clique nos quadrados A1, A2, B1, B2, etc. para filtrar
- 🌐 **Links diretos para Google** - Cada conferência tem botão que busca no Google
- ✨ **Botão de reset de filtros** - Limpe todos os filtros com um clique
- 📱 **Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- 🎨 **Design premium** - Tipografia elegante, cores vibrantes, animações suaves

---

## 🚀domínio

### **conf.ia.pro.br**

## ✨ Recursos principais

### **Efeito do Mouse**
- Ao mover o mouse, aparece um rastro brilhante colorido
- Automático e sem necessidade de configuração

### **Filtros (clique nos quadrados coloridos)**
- **A1** (Vermelho) - Conferências de excelência mundial
- **A2** (Laranja) - Conferências muito boas
- **A3** (Amarelo) - Conferências boas
- **A4** (Verde) - Conferências regulares
- **B1** (Cyan) - Pequena circulação
- **B2** (Azul) - Menor circulação
- **B3** (Roxo) - Circulação limitada
- **B4** (Cinza) - Local/Niche

### **Busca e Filtros Rápidos**
- Digite na barra de busca para encontrar por sigla ou nome
- Use os filtros rápidos (⭐ A1, 🏆 Tier A, etc.)
- Combine com o dropdown "Filtrar por Estrato"
- Clique em **✨ Limpar Tudo** para resetar todos os filtros

### **Botão Reset (Limpar Tudo)**
- Aparece no topo do painel de filtros
- Fica **desativado** quando não há filtros aplicados
- Fica **ativado** quando você aplica algum filtro
- Um clique restaura a visão completa de todas as conferências

### **Links para Google**
- Cada conferência tem um botão "🔗 Buscar"
- Clica uma vez e abre a busca no Google com sigla + nome
- Abre em uma nova aba (não sai do portal)

---

## 📊 Estatísticas em Tempo Real

O portal mostra:
- Total de conferências na base (1080+)
- Quantas conferências A1 existem
- Total de conferências Tier A
- Quantas conferências aparecem com o filtro atual

---

## 🎨 Customizações possíveis

### Mudar cores:
No arquivo, procure por `:root {` e altere as variáveis CSS:
```css
:root {
    --A1: #ef4444;        /* Cor A1 */
    --accent: #f97316;    /* Cor de destaque (laranja) */
    /* etc... */
}
```

### Adicionar mais conferências:
Procure por `const conferencias = [` e adicione mais linhas:
```javascript
{ sigla: 'SUACONF', nome: 'Nome Completo da Conferência', estrato: 'A1' },
```

---


## 📱 Responsividade

Testado em:
- ✅ Desktop (1920px+)
- ✅ Laptop (1024px - 1920px)
- ✅ Tablet (768px - 1024px)
- ✅ Mobile (até 768px)

---

## ⚡ Performance

- Arquivo pequeno (único HTML)
- Carrega instantaneamente
- Sem dependências externas pesadas
- Animações otimizadas com CSS

---

--

## 🆘 Dúvidas frequentes

**P: O efeito do mouse funciona em mobile?**
R: Não funciona em mobile (touch não tem movimento de mouse), mas o portal continua totalmente funcional.

**P: Preciso de internet para usar?**
R: Sim, precisa de internet para acessar o site e também para fazer as buscas no Google.

**P: Posso modificar o código?**
R: Sim! É um arquivo HTML puro, totalmente modificável.

**P: Como adiciono minhas próprias conferências?**
R: Adicione linhas no array `conferencias` dentro da tag `<script>`.

---

## 📧 Suporte

Para dúvidas ou sugestões:
- **Maiquel Gomes**: https://maiquelgomes.com.br
- **IA PRO**: https://ia.pro.br

---

**Aproveite o portal Conf PRO! 🚀**
