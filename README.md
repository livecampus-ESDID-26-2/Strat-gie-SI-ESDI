# Stratégie SI — Modalités des livrables

## Types de travaux

| Type | Modalité | Description |
|------|----------|-------------|
| **Ateliers** | Travail de **groupe** | Livrables de groupe, atelier par atelier |

---

## Nomenclature des fichiers

Respecter strictement le format suivant pour chaque dépôt (PDF) :

```text
NOM_DU_COURS_NOM1_NOM2_ATELIER_N_G1.pdf
```

**Exemples :**

```text
STRATEGIE_SI_BADET_MASIA_ATELIER_1_G1.pdf
STRATEGIE_SI_BADET_MASIA_ATELIER_2_G1.pdf
```

> Inclure **tous les noms de famille** des membres du groupe, **par ordre alphabétique**.  
> Remplacer `G1` par le numéro de votre groupe (`G1`, `G2`, etc.).

---

## Règles de nommage

- Tout en **MAJUSCULES**
- Séparateurs : **underscores** (`_`) uniquement
- Pas d'accents, d'espaces ni de caractères spéciaux
- Extension finale : `.pdf`

---

## Organisation du dépôt

```text
cours/       → supports de cours (chapitres)
ateliers/    → livrables de groupe (brouillons Markdown)
sources/     → PDF / documents d'origine
pdf/         → livrables PDF générés
docs/        → mini-app HTML (bibliothèque + pages statiques)
scripts/     → outils (conversion MD → PDF / HTML)
images/      → logo et photos des membres (prenom_nom.png)
```

## Génération des PDF et de la mini-app

Depuis la racine du projet :

```bash
./scripts/convert_to_pdf.sh
```

Le script :

1. Convertit **tous** les `.md` de `ateliers/` en PDF A4 (`pdf/`), avec page de garde et sommaire
2. Génère aussi des **pages HTML** (même style CSS que le PDF) pour `cours/` et `ateliers/`
3. Met à jour `docs/manifest.json` et la bibliothèque `docs/index.html`
4. Crée un fichier `EMAIL_*.txt` prêt à envoyer au professeur

Options :

```bash
./scripts/convert_to_pdf.sh --html-only   # mini-app seulement (pas besoin de Chrome)
./scripts/convert_to_pdf.sh --pdf-only    # PDF seulement
```

Prévisualisation locale :

```bash
python3 -m http.server 8000 --directory docs
```

Puis ouvrir [http://localhost:8000](http://localhost:8000).

Le nom du professeur et son adresse mail se règlent en haut de `scripts/convert_to_pdf.py` (`PROFESSOR`, `EMAIL_TO`) et dans l'en-tête de chaque fichier de `ateliers/` (`**Professeur :**`).

Prérequis PDF : Google Chrome (ou Chromium / Edge) installé sur macOS.

## Publier la mini-app sur GitHub Pages

1. Pousser le dépôt sur GitHub (avec le dossier `docs/` généré).
2. Sur GitHub : **Settings → Pages**.
3. Source : **Deploy from a branch**.
4. Branch : `main` (ou `master`), dossier **/docs**.
5. Enregistrer ; l'URL sera du type `https://<user>.github.io/<repo>/`.

Après chaque modification de cours / atelier : relancer le script, committer `docs/`, puis pousser.
