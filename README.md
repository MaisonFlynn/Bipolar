## Installation

```bash
git clone https://github.com/MaisonFlynn/Moodifier.git
cd Moodifier
```

## Configuration

1. [Generate New Token (Classic)](https://github.com/settings/tokens), Select "User" Scope & Generate Token

2. Repository Settings → Secrets & Variables → Actions → New Repository Secret
- Name: `SHUSH`
- Secret: `[Personal Access Token]`

3. Customize "Stuff" (Optional)
```
const stuff = [
  "💭 Ponderin'",
  "🎯 Dialled",
  "🧩 Perplexed",
  "☁️ Cloud 9"
];
```

Automated Workflow **Daily** @ **12AM UTC**!
