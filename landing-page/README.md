# AYA Home Resort - Landing Page Moderna

Landing page interativa e moderna para apresentação da análise estratégica completa do empreendimento AYA Home Resort.

## 🚀 Tecnologias

- **Next.js 14** - Framework React
- **TypeScript** - Tipagem estática
- **Tailwind CSS** - Estilização utility-first
- **shadcn/ui** - Componentes UI modernos
- **Lucide React** - Ícones
- **Framer Motion** - Animações (opcional)

## 📋 Funcionalidades

✅ **Menu Ancorado** (Sticky Navigation)
- Navegação suave entre seções
- Indicação visual da seção ativa
- Responsivo mobile

✅ **Bento Grid**
- Cards informativos com estatísticas principais
- Design moderno e clean
- Hover effects

✅ **22 Amenities**
- Cards individuais para cada amenity
- Ícones personalizados
- Animações de hover

✅ **Gráficos e Dados**
- Análise de mercado visual
- Matriz competitiva
- Projeções de vendas

✅ **Design Responsivo**
- Mobile-first
- Tablets e desktops
- Breakpoints otimizados

✅ **Efeitos Visuais**
- Gradientes animados
- Animações de scroll
- Transições suaves
- Glassmorphism

## 🛠️ Instalação

```bash
# Navegue até a pasta
cd landing-page

# Instale as dependências
npm install

# Execute em modo de desenvolvimento
npm run dev

# Acesse em
http://localhost:3000
```

## 📁 Estrutura do Projeto

```
landing-page/
├── src/
│   ├── app/
│   │   ├── page.tsx          # Página principal
│   │   ├── layout.tsx        # Layout global
│   │   └── globals.css       # Estilos globais
│   ├── components/
│   │   └── ui/               # Componentes shadcn
│   │       ├── button.tsx
│   │       └── card.tsx
│   └── lib/
│       └── utils.ts          # Utilitários
├── public/                   # Arquivos estáticos
├── tailwind.config.ts        # Configuração Tailwind
├── tsconfig.json             # Configuração TypeScript
└── package.json              # Dependências
```

## 🎨 Seções da Landing Page

### 1. Hero Section
- Título principal com gradiente animado
- Bento grid com 4 stats principais
- CTAs para análise e contato

### 2. Produto
- Especificações técnicas (114m²)
- 12 diferenciais principais
- Localização estratégica

### 3. Amenities
- Grid com 22 cards
- Ícones Lucide
- Hover effects

### 4. Análise de Mercado
- 3 cards (Ribeirão Pires, ABC, SP Capital)
- Dados demográficos
- Insight crítico destacado

### 5. Matriz Competitiva
- Tabela comparativa
- AYA vs concorrentes
- Vantagens e desafios

### 6. Estratégia de Campanhas
- 4 públicos-alvo
- Budget allocation
- Projeções de vendas (3 cenários)

### 7. Contato/CTA
- Informações de contato
- Recomendação final
- CTA para relatório completo

### 8. Footer
- Informações do empreendimento
- Links de contato
- Copyright

## 🎯 Customização

### Cores
Edite `tailwind.config.ts` para alterar o tema de cores:

```typescript
colors: {
  primary: {...},
  secondary: {...},
  // ...
}
```

### Conteúdo
Edite `src/app/page.tsx` para alterar textos, dados e imagens.

### Componentes
Adicione novos componentes em `src/components/ui/` seguindo o padrão shadcn.

## 📊 Dados Apresentados

- **Produto:** 96 unidades, 114m², 22 amenities, R$ 800k
- **Mercado:** 119k habitantes (RP), 2,5M (ABC), público-alvo 1.210-3.110 famílias
- **Competitiva:** AYA vs Reserva São Caetano vs Wine Santo André
- **Estratégia:** 4 públicos, budget R$ 351k, projeção 18 vendas
- **ROI:** 180% (conservador) a 891% (otimista)

## 🚀 Deploy

### Vercel (Recomendado)

```bash
# Faça login na Vercel
vercel login

# Deploy
vercel --prod
```

### Build para produção

```bash
npm run build
npm run start
```

## 📝 Notas

- Todos os dados apresentados são baseados no relatório técnico completo
- Design otimizado para apresentação ao cliente
- Pode ser facilmente convertido em PDF ou apresentação
- Pronto para ser hospedado em qualquer plataforma

## 👤 Autor

**RPK Agência**
- Analista: Kelvin Nascimento
- Data: 08/12/2025
- Cliente: AYA Home Resort / WIND Incorporadora

## 📄 Licença

Uso interno - RPK Agência © 2025
