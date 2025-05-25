# AI Code Reviewer Pro

Pokročilý nástroj pro analýzu kvality kódu s AI funkcemi, multi-language podporou a automatickým testováním.

## 🚀 Funkce

- **Multi-Language Support**: JavaScript, Python, Java, TypeScript, C#, Go
- **AI Pattern Recognition**: Self-learning systém pro detekci problémů v kódu
- **Automatické testování**: AI generuje test cases na základě analyzovaného kódu
- **Real-time analýza**: Okamžitá zpětná vazba s metrikami kvality
- **Self-Learning AI**: Systém se učí z každé analýzy a zlepšuje přesnost

## 🛠️ Technologie

- **Frontend**: React 18, Tailwind CSS
- **Icons**: Lucide React
- **AI Features**: Pattern matching, confidence scoring, automated learning
- **Testing**: Automated test case generation

## 📦 Instalace

### Požadavky
- Node.js 16+
- npm nebo yarn

### Setup
```bash
# Klonování projektu
git clone [repository-url]
cd ai-code-reviewer

# Instalace dependencies
npm install

# Spuštění development serveru
npm start
```

### Dependencies
```bash
npm install lucide-react tailwindcss postcss autoprefixer
```

## 🎯 Použití

1. **Vyberte programovací jazyk** z dostupných možností
2. **Vložte váš kód** do editoru (nebo použijte ukázkový kód)
3. **Analyzujte kód** - AI detekuje problémy a poskytne doporučení
4. **Spusťte testy** - automaticky generované test cases
5. **Sledujte AI learning** - systém se učí z každé analýzy

## 🧠 AI Funkce

### Pattern Recognition
- Detekce neefektivních algoritmů (např. exponenciální rekurze)
- Identifikace deprecated syntaxe (var vs let/const)
- Security vulnerability detection
- Performance anti-patterns

### Self-Learning System
- Confidence scoring pro každou detekci
- Automatické učení nových vzorů
- Tracking accuracy metrics
- Dynamic knowledge base pro každý jazyk

### Automated Testing
- Generování test cases na základě funkční struktury
- Performance testing pro algoritmy
- Coverage simulation
- AI-powered edge case detection

## 📊 Metriky

Aplikace poskytuje následující metriky kvality kódu:
- **Complexity**: Složitost kódu
- **Maintainability**: Udržovatelnost
- **Performance**: Výkonnost
- **Security**: Bezpečnost

## 🏗️ Architektura

```
src/
├── components/
│   └── AICodeReviewer.jsx    # Hlavní komponenta
├── App.js                    # Root aplikace
├── index.js                  # Entry point
└── index.css                 # Tailwind styles
```

## 🎨 Customization

### Přidání nového jazyka
```javascript
const LANGUAGE_CONFIGS = {
  // ... existující jazyky
  rust: {
    name: 'Rust',
    icon: '🦀',
    testRunner: 'cargo',
    commonIssues: ['ownership', 'lifetimes'],
    extensions: ['.rs']
  }
};
```

### Rozšíření AI patterns
```javascript
knowledgeBaseRef.current.javascript.patterns.push({
  pattern: /your-regex-pattern/,
  issue: 'issue_type',
  confidence: 0.85
});
```

## 🚀 Deployment

### Vercel
```bash
npm run build
npx vercel
```

### Netlify
```bash
npm run build
netlify deploy --prod --dir=build
```

### Docker
```dockerfile
FROM node:16-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD ["npm", "start"]
```

## 📈 Budoucí Funkce

- [ ] Backend integrace s real-time code execution
- [ ] Git integration pro pull request reviews
- [ ] Team collaboration features
- [ ] Advanced security scanning
- [ ] Performance benchmarking
- [ ] Code quality reporting
- [ ] IDE extensions (VS Code, IntelliJ)

## 🤝 Přispívání

1. Fork the repository
2. Vytvořte feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Otevřete Pull Request

## 📄 Licence

Distributed under the MIT License. See `LICENSE` for more information.

## 👨‍💻 Autoři

- **Lukáš Drštička** - *Initial work and development*
- **Claude (Anthropic)** - *AI assistance and code review logic*

## 📞 Kontakt
lukas.drsticka@gmail.com
+ 420 721624429
