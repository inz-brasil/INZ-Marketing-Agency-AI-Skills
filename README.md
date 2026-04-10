# 🚀 Marketing Agency AI Skills

> **Transform any AI IDE into a complete marketing agency powerhouse**

A professional collection of 23+ AI skills covering copywriting, design, SEO, strategy, conversion optimization, and media production. Compatible with Claude, Antigravity, Cursor, Windsurf, Copilot, and any AI agent that supports markdown-based skills.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skills: 23+](https://img.shields.io/badge/Skills-23+-blue.svg)]()
[![Categories: 6](https://img.shields.io/badge/Categories-6-green.svg)]()

---

## 📋 Table of Contents

- [What's Included](#whats-included)
- [Quick Start](#quick-start)
- [Installation by IDE](#installation-by-ide)
- [Skills Overview](#skills-overview)
- [Workflows](#workflows)
- [Usage Examples](#usage-examples)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 What's Included

### 23 Professional Skills Across 6 Categories:

| Category | Skills | Use Cases |
|----------|--------|-----------|
| **📝 Copywriting & Content** | 5 skills | Social media, landing pages, emails, ads, content strategy |
| **🎨 Design & Visual** | 5 skills | UI/UX, branding, prototypes, graphics, visual identity |
| **🔍 SEO & Optimization** | 4 skills | Technical SEO, audits, schema markup, programmatic SEO |
| **📈 Marketing Strategy** | 4 skills | 139 marketing ideas, psychology, paid ads, competitor analysis |
| **🎯 Conversion & Analytics** | 4 skills | A/B testing, analytics tracking, CRO, form optimization |
| **🎬 Media Production** | 2 skills | Video downloads, image enhancement |

**Total:** 23+ skills covering 100% of marketing agency needs

---

## ⚡ Quick Start

### 1. Clone or Download

```bash
git clone https://github.com/your-username/Marketing-Agency-AI-Skills.git
cd Marketing-Agency-AI-Skills
```

### 2. Choose Your Installation Method

Pick your AI IDE and follow the specific instructions below:

- [Kiro](#kiro)
- [Antigravity / Gemini CLI](#antigravity--gemini-cli)
- [Claude Code](#claude-code)
- [Cursor](#cursor)
- [Windsurf](#windsurf)
- [GitHub Copilot](#github-copilot)
- [Universal (Any AI Agent)](#universal-any-ai-agent)

---

## 📦 Installation by IDE

### Kiro

```bash
# Copy skills to your project
cp -r Marketing-Agency-AI-Skills/* your-project/.kiro/skills/

# Or create symlink
ln -s $(pwd)/Marketing-Agency-AI-Skills your-project/.kiro/skills/marketing
```

**Structure:**
```
your-project/
└── .kiro/
    └── skills/
        ├── copywriting/
        ├── frontend-design/
        ├── seo-fundamentals/
        └── ... (all skills)
```

---

### Antigravity / Gemini CLI

```bash
# Copy to .agent directory
cp -r Marketing-Agency-AI-Skills/* your-project/.agent/skills/
```

**Structure:**
```
your-project/
└── .agent/
    └── skills/
        ├── copywriting/
        ├── frontend-design/
        └── ... (all skills)
```

**Usage:**
```
@[/copywriting] Write a landing page for a SaaS product
```

---

### Claude Code

In Claude Code, skills become commands:

```bash
# Create commands directory
mkdir -p your-project/.claude/commands/

# Copy each skill as a command
cp Marketing-Agency-AI-Skills/copywriting/SKILL.md your-project/.claude/commands/copywriting.md
cp Marketing-Agency-AI-Skills/frontend-design/SKILL.md your-project/.claude/commands/frontend-design.md
# ... repeat for all skills
```

**Structure:**
```
your-project/
└── .claude/
    └── commands/
        ├── copywriting.md
        ├── frontend-design.md
        └── ... (all skills)
```

**Usage:**
```
/copywriting Write a landing page
```

---

### Cursor

```bash
# Copy skills to project root
cp -r Marketing-Agency-AI-Skills/skills your-project/skills/

# Create .cursorrules file (optional but recommended)
cat > your-project/.cursorrules << 'EOF'
# Marketing Agency AI Skills
You have access to professional marketing skills in the /skills directory.
Use them to provide expert marketing, design, and SEO assistance.
EOF
```

**Structure:**
```
your-project/
├── .cursorrules
└── skills/
    ├── copywriting/
    ├── frontend-design/
    └── ... (all skills)
```

**Usage:**
```
Use @copywriting to write a landing page
```

---

### Windsurf

```bash
# Copy skills
cp -r Marketing-Agency-AI-Skills/* your-project/.windsurf/skills/

# Create .windsurfrules
cat > your-project/.windsurfrules << 'EOF'
# Marketing Agency AI Skills
Professional marketing skills available in .windsurf/skills/
EOF
```

**Structure:**
```
your-project/
├── .windsurfrules
└── .windsurf/
    └── skills/
        ├── copywriting/
        └── ... (all skills)
```

---

### GitHub Copilot

```bash
# Create instructions directory
mkdir -p your-project/.github/

# Copy skills
cp -r Marketing-Agency-AI-Skills/* your-project/.github/skills/

# Create copilot-instructions.md
cat > your-project/.github/copilot-instructions.md << 'EOF'
# Marketing Agency AI Skills
You have access to professional marketing skills in .github/skills/
Use them to provide expert assistance.
EOF
```

**Structure:**
```
your-project/
└── .github/
    ├── copilot-instructions.md
    └── skills/
        ├── copywriting/
        └── ... (all skills)
```

---

### Universal (Any AI Agent)

For any AI that supports RAG or document context:

1. **Upload the entire `Marketing-Agency-AI-Skills` folder** to your AI workspace
2. **Set system prompt** with the contents of `SYSTEM_PROMPT.md` (included)
3. **Reference skills** by mentioning their names in your prompts

---

## 🎨 Skills Overview

### 📝 Copywriting & Content

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **copywriting** | Write marketing copy that converts | Headlines, CTAs, landing pages, ads, humanized text |
| **copy-editing** | Edit and improve existing copy | Systematic review, eliminate jargon, improve clarity |
| **email-sequence** | Create email marketing campaigns | Drip campaigns, nurture sequences, automation |
| **social-content** | Social media content creation | LinkedIn, Twitter, Instagram, TikTok, calendars |
| **content-strategy** | Plan content strategy | Topic clusters, editorial planning, gap analysis |

### 🎨 Design & Visual

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **frontend-design** | Design thinking and decisions | Color psychology, typography, UX, animations |
| **ui-ux-pro-max** | Complete design intelligence | 50 styles, 21 palettes, 50 font pairings, 20 charts |
| **web-artifacts-builder** | Interactive prototypes | React + TypeScript + Tailwind, 40+ components |
| **canvas-design** | Visual art creation | Posters, graphics, PNG/PDF designs |
| **brand-guidelines** | Brand identity application | Official colors, typography, visual standards |

### 🔍 SEO & Optimization

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **seo-fundamentals** | SEO basics and best practices | E-E-A-T, Core Web Vitals, technical SEO |
| **seo-audit** | Complete SEO audits | Diagnostics, technical SEO, on-page optimization |
| **schema-markup** | Structured data implementation | Schema.org, JSON-LD, rich snippets |
| **programmatic-seo** | SEO at scale | Template pages, directory pages, mass optimization |

### 📈 Marketing Strategy

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **marketing-ideas** | 139 marketing strategies | Tested tactics, growth hacking, acquisition channels |
| **marketing-psychology** | 70+ mental models | Consumer psychology, cognitive biases, persuasion |
| **paid-ads** | Paid advertising campaigns | Google Ads, Meta, LinkedIn, Twitter/X, ROAS optimization |
| **competitor-alternatives** | Comparison pages | "X vs Y", "X alternative", competitive SEO |

### 🎯 Conversion & Analytics

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **ab-test-setup** | A/B testing and experiments | Hypothesis design, variants, statistical analysis |
| **analytics-tracking** | Analytics implementation | GA4, event tracking, conversion tracking, UTM, GTM |
| **form-cro** | Form optimization | Lead capture, contact forms, friction reduction |
| **page-cro** | Page conversion optimization | CRO, landing pages, homepage, pricing optimization |

### 🎬 Media Production

| Skill | Description | Key Features |
|-------|-------------|--------------|
| **video-downloader** | YouTube video downloads | Multiple qualities, formats, audio-only MP3 |
| **image-enhancer** | Image quality improvement | Resolution, sharpness, clarity, screenshot optimization |

---

## 🔄 Workflows

### Workflow 1: Complete Landing Page

```
1. content-strategy → Plan content
2. copywriting → Create texts and CTAs
3. frontend-design → Define visual style
4. ui-ux-pro-max → Choose palette and typography
5. seo-fundamentals → Optimize for SEO
6. web-artifacts-builder → Create prototype
7. analytics-tracking → Implement tracking
8. ab-test-setup → Prepare A/B tests
```

### Workflow 2: Social Media Campaign

```
1. marketing-psychology → Understand audience
2. content-strategy → Plan calendar
3. social-content → Create posts
4. canvas-design → Create visual art
5. copy-editing → Review texts
```

### Workflow 3: Paid Ads Campaign

```
1. marketing-ideas → Strategy brainstorming
2. paid-ads → Structure campaigns
3. copywriting → Create ad copy
4. page-cro → Optimize landing page
5. analytics-tracking → Configure tracking
6. ab-test-setup → Test variations
```

### Workflow 4: SEO Content Strategy

```
1. seo-audit → Audit current site
2. content-strategy → Plan topics
3. programmatic-seo → Create pages at scale
4. copywriting → Write content
5. schema-markup → Implement structured data
6. seo-fundamentals → Technical optimization
```

---

## 💡 Usage Examples

### Example 1: Landing Page for Beauty Clinic

```
"Create a landing page for a professional skincare clinic"

AI will activate:
- copywriting → Persuasive texts
- frontend-design → Elegant visual style
- ui-ux-pro-max → Beauty/wellness palette
- seo-fundamentals → SEO optimization
```

### Example 2: Instagram Posts for Fashion Brand

```
"I need 10 Instagram posts for a fashion brand"

AI will activate:
- social-content → Post creation
- copywriting → Engaging captions
- canvas-design → Visual art
```

### Example 3: SEO Audit

```
"Perform an SEO audit on my website"

AI will activate:
- seo-audit → Complete diagnostics
- seo-fundamentals → Technical recommendations
- schema-markup → Structured data suggestions
```

---

## 📊 Project Structure

```
Marketing-Agency-AI-Skills/
├── README.md                          # This file
├── LICENSE                            # MIT License
├── SYSTEM_PROMPT.md                   # Universal system prompt
├── INSTALLATION_GUIDE.md              # Detailed installation guide
├── WORKFLOWS.md                       # Complete workflow examples
├── CHANGELOG.md                       # Version history
│
├── copywriting/
│   ├── SKILL.md                       # Main skill file
│   └── references/                    # Additional resources
│
├── copy-editing/
│   ├── SKILL.md
│   └── references/
│
├── email-sequence/
│   ├── SKILL.md
│   └── references/
│
├── social-content/
│   ├── SKILL.md
│   └── references/
│
├── content-strategy/
│   └── SKILL.md
│
├── frontend-design/
│   ├── SKILL.md
│   ├── color-system.md
│   ├── typography-system.md
│   ├── visual-effects.md
│   ├── animation-guide.md
│   └── ux-psychology.md
│
├── ui-ux-pro-max/
│   ├── SKILL.md
│   ├── data/                          # Design database
│   └── scripts/                       # Python search scripts
│
├── web-artifacts-builder/
│   ├── SKILL.md
│   └── scripts/                       # Build scripts
│
├── canvas-design/
│   ├── SKILL.md
│   └── canvas-fonts/
│
├── brand-guidelines/
│   └── SKILL.md
│
├── seo-fundamentals/
│   ├── SKILL.md
│   └── scripts/
│
├── seo-audit/
│   ├── SKILL.md
│   └── references/
│
├── schema-markup/
│   ├── SKILL.md
│   └── references/
│
├── programmatic-seo/
│   ├── SKILL.md
│   └── references/
│
├── marketing-ideas/
│   ├── SKILL.md
│   └── references/
│
├── marketing-psychology/
│   └── SKILL.md
│
├── paid-ads/
│   ├── SKILL.md
│   └── references/
│
├── competitor-alternatives/
│   ├── SKILL.md
│   └── references/
│
├── ab-test-setup/
│   ├── SKILL.md
│   └── references/
│
├── analytics-tracking/
│   ├── SKILL.md
│   └── references/
│
├── form-cro/
│   └── SKILL.md
│
├── page-cro/
│   ├── SKILL.md
│   └── references/
│
├── video-downloader/
│   ├── SKILL.md
│   └── scripts/
│
└── image-enhancer/
    └── SKILL.md
```

---

## 🎓 How Skills Work

Skills are activated automatically when you mention related keywords:

**Automatic Activation:**
- "Create a landing page" → Activates copywriting, frontend-design, seo-fundamentals
- "I need Instagram posts" → Activates social-content, copywriting
- "SEO audit" → Activates seo-audit, seo-fundamentals
- "Create an ad campaign" → Activates paid-ads, copywriting, analytics-tracking

**Manual Activation:**
```
"Use @copywriting and @frontend-design to create a landing page"
```

---

## 🔧 Requirements

### Minimum Requirements:
- Any AI IDE that supports markdown-based skills or RAG
- No additional dependencies for basic skills

### Optional Requirements:
- **Python 3.8+** (for ui-ux-pro-max search scripts)
- **Node.js 18+** (for web-artifacts-builder)

---

## 📈 Compatibility Matrix

| IDE / Agent | Compatibility | Installation Method | Activation |
|-------------|---------------|---------------------|------------|
| **Kiro** | ✅ Full | `.kiro/skills/` | Automatic |
| **Antigravity** | ✅ Full | `.agent/skills/` | `@[/skill-name]` |
| **Claude Code** | ✅ Full | `.claude/commands/` | `/skill-name` |
| **Cursor** | ✅ Full | `skills/` + `.cursorrules` | `@skill-name` |
| **Windsurf** | ✅ Full | `.windsurf/skills/` | Automatic |
| **GitHub Copilot** | ✅ Full | `.github/skills/` | Mention in prompt |
| **ChatGPT** | ⚠️ Partial | Upload folder | Mention in prompt |
| **Claude Web** | ⚠️ Partial | Upload folder | Mention in prompt |
| **Any RAG-enabled AI** | ✅ Full | Upload folder | Mention in prompt |

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Adding New Skills

1. Fork the repository
2. Create a new skill folder: `new-skill-name/`
3. Add `SKILL.md` with the skill content
4. Follow the existing skill structure
5. Update README.md with the new skill
6. Submit a pull request

### Improving Existing Skills

1. Fork the repository
2. Make your improvements
3. Test with multiple AI IDEs
4. Submit a pull request with detailed description

### Reporting Issues

- Use GitHub Issues
- Provide IDE/agent version
- Include reproduction steps
- Share error messages

---

## 📝 License

MIT License - see [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Private use

Just keep the license and copyright notice.

---

## 🌟 Credits

Created by **INZ Brasil** ([@inzbrasil](https://instagram.com/inzbrasil))

Special thanks to:
- The AI community for feedback and contributions
- All IDE developers for making skills possible
- Marketing professionals who tested these skills

---

## 📞 Support

- **Issues:** [GitHub Issues](https://github.com/your-username/Marketing-Agency-AI-Skills/issues)
- **Discussions:** [GitHub Discussions](https://github.com/your-username/Marketing-Agency-AI-Skills/discussions)
- **Instagram:** [@inzbrasil](https://instagram.com/inzbrasil)

---

## 🚀 What's Next?

### Upcoming Skills:
- [ ] Video editing automation
- [ ] Podcast production
- [ ] Influencer outreach
- [ ] PR & media relations
- [ ] Event marketing
- [ ] Affiliate marketing

### Upcoming Features:
- [ ] Skill templates generator
- [ ] Custom workflow builder
- [ ] Performance analytics
- [ ] Multi-language support

---

## ⭐ Star History

If you find this useful, please star the repository!

[![Star History Chart](https://api.star-history.com/svg?repos=your-username/Marketing-Agency-AI-Skills&type=Date)](https://star-history.com/#your-username/Marketing-Agency-AI-Skills&Date)

---

## 📚 Additional Resources

- [Complete Workflows Guide](WORKFLOWS.md)
- [Installation Guide](INSTALLATION_GUIDE.md)
- [Changelog](CHANGELOG.md)
- [Contributing Guidelines](CONTRIBUTING.md)

---

**Made with ❤️ for the marketing community**

Transform your AI into a complete marketing agency. Start creating amazing content today! 🚀
