# Charte graphique — Festival Horizon 2027

Ce document définit l'identité visuelle du site. Toutes les valeurs sont disponibles
sous forme de variables CSS dans `style.css` (bloc `:root`) : **utilisez toujours les
variables plutôt que des valeurs en dur.**

## 🎨 Couleurs

| Rôle               | Nom      | Hex       | Variable CSS        |
|--------------------|----------|-----------|---------------------|
| Fond sombre        | Nuit     | `#1B1B3A` | `--color-night`     |
| Accent principal   | Sunset   | `#FF6B35` | `--color-sunset`    |
| Accent secondaire  | Magenta  | `#E63973` | `--color-magenta`   |
| Mise en avant      | Or       | `#FFC857` | `--color-gold`      |
| Fond clair         | Crème    | `#FFF8F0` | `--color-cream`     |
| Texte principal    | —        | `#22223B` | `--color-text`      |
| Texte secondaire   | —        | `#6C6C80` | `--color-muted`     |
| Bordures           | —        | `#E4DCD2` | `--color-border`    |

**Dégradé signature « Horizon »** (`--gradient-horizon`) : Nuit → Magenta → Sunset, à 135°.
À utiliser pour le header, le footer et les bandeaux.

## 🔤 Typographies

| Usage    | Police      | Variable        |
|----------|-------------|-----------------|
| Titres   | Bebas Neue  | `--font-title`  |
| Texte    | Inter       | `--font-body`   |

Tailles : `--fs-h1`, `--fs-h2`, `--fs-h3`, `--fs-body`, `--fs-small`.

- `h1` : titre principal, blanc sur fond sombre
- `h2` : titres de section, couleur Nuit
- `h3` : sous-titres, couleur Sunset

## 📏 Espacements

`--space-xs` (0.25rem) · `--space-sm` (0.5rem) · `--space-md` (1rem) · `--space-lg` (2rem) · `--space-xl` (4rem)

## 🧩 Composants disponibles

| Classe           | Usage                                        |
|------------------|----------------------------------------------|
| `.container`     | Centre le contenu (max 1200px)               |
| `.btn .btn-primary`   | Bouton principal (billetterie, CTA)     |
| `.btn .btn-secondary` | Bouton secondaire                       |
| `.card`          | Carte artiste / concert                      |
| `.badge`         | Étiquette (date, genre musical)              |
| `.section-dark`  | Section sur fond dégradé Horizon             |

## ✅ Règles

- Contraste : texte clair uniquement sur fond Nuit ou dégradé ; texte foncé sur Crème/blanc.
- L'Or est réservé aux petits éléments (badges, dates) — jamais pour du texte long.
- Coins arrondis : `--radius-md` pour les cartes, `--radius-pill` pour les boutons.
