# Tidjan Tokpa — Portfolio

Portfolio personnel de développeur web full stack, construit avec Jekyll et le thème Agency (Bootstrap 4).

## Stack technique

- **Generateur statique** : Jekyll 4.x
- **Theme** : [jekyll-agency](https://github.com/raviriley/agency-jekyll-theme) (gem)
- **Frontend** : Bootstrap 4, jQuery, SCSS custom
- **Polices** : Google Fonts (Montserrat, Kaushan Script, Droid Serif, Roboto Slab)
- **Icones** : Font Awesome 5
- **Formulaire contact** : Formspree
- **Deploiement** : GitHub Pages

## Structure du projet

```
_config.yml          # Configuration Jekyll (titre, email, locale, theme)
_data/
  sitetext.yml       # Tous les textes du site (sections, timeline, about, contact)
  navigation.yml     # Liens de navigation et URLs personnalisees
  style.yml          # Couleurs, polices, images de fond
_portfolio/          # Fiches projets au format Markdown
  healthmate.md      # SaaS medical IA
  pickup.md          # Marketplace urbaine
  frontalierpro.md   # SaaS pour frontaliers
_layouts/            # Templates de pages (default, home, page)
_includes/           # Composants HTML reutilisables (navbar, footer, sections)
_sass/               # Styles SCSS organises (base, components, layout)
assets/
  css/               # Bootstrap, Font Awesome, agency.scss
  js/                # jQuery, Bootstrap, validation formulaire
  img/               # Images portfolio, timeline, team
competences.md       # Page competences techniques
projects.md          # Page projets
vision.md            # Page vision et entrepreneuriat
```

## Prerequis

- **Ruby** >= 2.7
- **Bundler** (`gem install bundler`)
- **Jekyll** (installe via le Gemfile)

## Installation

```bash
git clone <url-du-repo>
cd Jekyll-Portfolio
bundle install
```

## Lancer en local

```bash
bundle exec jekyll serve
```

Le site est accessible sur [http://localhost:4000](http://localhost:4000).

Le serveur recharge automatiquement les modifications (sauf `_config.yml` qui necessite un redemarrage).

## Deploiement

Le projet est configure pour **GitHub Pages**. Un push sur la branche `main` declenche automatiquement le build et le deploiement.

## Personnalisation

| Quoi modifier | Fichier |
|---------------|---------|
| Textes du site (titre, sections, timeline) | `_data/sitetext.yml` |
| Navigation et URLs | `_data/navigation.yml` |
| Couleurs, polices, images de fond | `_data/style.yml` |
| Configuration globale (titre, email, locale) | `_config.yml` |
| Ajouter un projet | Creer un fichier `.md` dans `_portfolio/` |
| Ajouter une page | Creer un fichier `.md` a la racine avec le layout `page` |

## Licence

Theme base sur [Agency Jekyll Theme](https://github.com/raviriley/agency-jekyll-theme) — MIT License.
