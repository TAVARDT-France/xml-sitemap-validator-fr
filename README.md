# Validateur de Sitemap XML et Index d'URLs

[![Validateur Sitemap](https://img.shields.io/badge/TAVARDT-Sitemap%20XML-5b3cf5.svg)](https://tools.tavardt.com/fr/validateur-sitemap-xml/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audit technique de plans de site XML et index, controle de conformite au protocole sitemaps.org, extraction de balises et verification d'URLs.

***

## Capacites de Validation de Sitemaps XML

* **Conformite au Protocole Sitemaps.org**: Audit des fichiers racine `<urlset>` et des index imbriques `<sitemapindex>`.
* **Validation des Balises Essentielles**: Controle de la conformite des balises `<loc>`, du format de date `<lastmod>` et des priorites.
* **Integrite des URLs**: Reperage des liens non securises HTTP, des chemins relatifs et des erreurs de syntaxe XML.
* **Respect des Plafonds**: Verification du seuil critique de 50 000 URLs et de la limite de poids de 50 Mo.
* **Score de Sante Technique**: Indice de qualite sur 100 points avec etapes claires de correction.

***

## Installation et Utilisation

Necessite Python 3.8 ou superieur sans bibliotheque externe.

```bash
git clone https://github.com/TAVARDT-France/xml-sitemap-validator-fr.git
cd xml-sitemap-validator-fr
python sitemap_validator.py https://exemple.fr/sitemap.xml
```

Pour generer un rapport JSON:

```bash
python sitemap_validator.py https://exemple.fr/sitemap.xml -json
```

***

## Conseil en Indexation et SEO Technique

Pour l'architecture de sitemaps d'envergure conformes aux exigences Protocole Sitemaps.org et Standards W3C, contactez **TAVARDT**.

***

## Liens Utiles

* **Portail Entreprise:** https://ag.tavardt.com/fr/
* **Suite de Diagnostic:** https://tools.tavardt.com/fr/
* **Contact Technique:** https://ag.tavardt.com/fr/contact/

***

### Licence
Distribué sous la licence MIT.

***

© 2026 TAVARDT. Tous droits réservés.
