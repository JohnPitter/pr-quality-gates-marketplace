<div align="center">

# PR Quality Gates — Marketplace

**Marketplace do Claude Code para o plugin `pr-quality-gates`.**

[![Claude Code](https://img.shields.io/badge/Claude%20Code-Marketplace-E8622C?style=flat-square)](https://claude.com/claude-code)
[![License](https://img.shields.io/badge/License-MIT-orange?style=flat-square)](#license)

</div>

---

## Instalação

```
/plugin marketplace add JohnPitter/pr-quality-gates-marketplace
/plugin install pr-quality-gates@pr-quality-gates
```

---

## Plugins disponíveis

| Plugin | Descrição | Versão |
|---|---|---|
| [`pr-quality-gates`](https://github.com/JohnPitter/pr-quality-gates) | 5 gates para validar PRs em projetos Go: CCN, cobertura, mutação, tamanho de módulos e acoplamento. | 0.1.0 |

---

## Estrutura

```
pr-quality-gates-marketplace/
  .claude-plugin/
    marketplace.json          # manifesto do marketplace
  plugins/
    pr-quality-gates/         # código do plugin (submodule / mirror)
  README.md
```

---

## License

MIT — use livremente.
