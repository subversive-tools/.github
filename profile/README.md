# Subversive Tools

**Redmine plugins for digital sovereignty.**

Small levers, free pie for all.

---

We build open-source Redmine plugins for teams that value autonomy, transparency, and control over their own data. No tracking. No vendor lock-in. No corporate surveillance.

## Plugins

| Plugin | Description | Status |
|--------|-------------|--------|
| [redmine_subskills](https://github.com/subversive-tools/redmine_subskills) | Skill management & role matrix | ✅ Stable |
| [redmine_submenus](https://github.com/subversive-tools/redmine_submenus) | Dropdown navigation & portfolio kanban | ✅ Stable |
| [redmine_subnavigation](https://github.com/subversive-tools/redmine_subnavigation) | Collapsible sidebar navigation | ✅ Stable |
| [redmine_subsimplify](https://github.com/subversive-tools/redmine_subsimplify) | Simplified UI for specific roles | ✅ Stable |
| [redmine_subwikifiles](https://github.com/subversive-tools/redmine_subwikifiles) | Bidirectional wiki-to-markdown sync | ⚠️ Beta |

## Installation

```bash
cd /path/to/redmine/plugins
git clone https://github.com/subversive-tools/<plugin-name>.git
bundle install
bundle exec rake redmine:plugins:migrate RAILS_ENV=production
```

## Philosophy

Built for NGOs, activists, and privacy-conscious teams questioning systems — not cementing them. Developed by [Stefan Mischke (modoq)](https://github.com/modoq). No startup, no VC funding, no exit strategy. Just tools that work.

🌐 [subversive-tools.github.io](https://subversive-tools.github.io) · ✉️ subversive-tools@ikmail.com · MIT License
