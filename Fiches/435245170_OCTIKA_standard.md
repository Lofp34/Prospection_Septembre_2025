---
siren: "435245170"
siret_siege: "43524517000012"
denomination: "OCTIKA"
marques: ["Octika Eyewear"]
naf: "46.43Z"
section_naf: "G"
nature_juridique:
  code: "5710"
  libelle: "SAS"
date_creation: "2001-03-22"
statut: "A"
categorie_entreprise:
  valeur: "PME"
  annee: 2022
adresse:
  ligne: "121 RUE GEORGES GUYNEMER"
  cp: "34130"
  commune_insee: "34154"
  departement: "34"
  region: "76"
  epci: "243400470"
  geo:
    lat: 43.584785
    lon: 3.939612
contacts:
  site_web: "https://www.octika.com"
  emails: ["contact@octika.com"]
effectifs:
  tranche_code: "12"
  annee: 2022
etablissements:
  total: 2
  ouverts: 2
idcc: ["0573"]
dirigeance:
  president:
    type: "personne morale"
    denomination: "FIVE VISION"
    siren: "904391877"
    activite: "70.10Z"
    siege_adresse: "121 Rue Georges Guynemer 34130 Mauguio"
    dirigeants:
      - type: "personne physique"
        nom: "CINQUEGRANA"
        prenoms: "STEFANO"
        qualite: "Gérant"
        date_naissance: "1968-07"
        nationalite: "Italienne"
  commissaires_aux_comptes:
    titulaire:
      denomination: "CABINET PHS"
      siren: "444175699"
    suppleant:
      denomination: "JP AUDIT"
      siren: "795217256"
finances:
  - annee: 2024
    ca_eur: 12381245
    resultat_net_eur: 2689219
scores:
  priorite: 8
  fit_icp: 4
tags: ["34130","CA_5_20M","siege","Distribution"]
sources:
  - "API recherche-entreprises.data.gouv.fr (search?q=435245170 / 904391877 / 444175699 / 795217256)"
  - "Fiche interne 435245170_OCTIKA.md"
---

## 1) Identité et résumé exécutif
Distributeur B2B d'optique (montures et accessoires) basé à Mauguio. Statut actif. Société par actions simplifiée (SAS), catégorie PME. Positionnement orienté opticiens indépendants et réseaux, avec marque propriétaire "Octika Eyewear" et service client internalisé.

## 2) Siège social et périmètre
- SIRET siège: 43524517000012
- Adresse: 121 Rue Georges Guynemer, 34130 Mauguio (INSEE 34154) — dép. 34, région 76, EPCI 243400470
- Coordonnées: 43.584785, 3.939612
- Établissements: 2 (ouverts: 2)

## 3) Activité (NAF/Section)
- NAF: 46.43Z — Section: G
- Interprétation: distribution B2B d'optique (montures de vue/solaire, accessoires)

## 4) Dirigeance
- Président (personne morale): FIVE VISION (SIREN 904391877, APE 70.10Z)
  - Siège FIVE VISION: 121 Rue Georges Guynemer, 34130 Mauguio
  - Dirigeant de FIVE VISION: Stefano CINQUEGRANA (personne physique), Gérant, né 1968-07, nationalité italienne
- Commissaires aux comptes:
  - Titulaire: CABINET PHS (SIREN 444175699)
  - Suppléant: JP AUDIT (SIREN 795217256)

## 5) Effectifs
- Tranche effectif (code): 12 (année 2022)
- Convention collective (IDCC): 0573 (renseignée)

## 6) Données financières
| Année | Chiffre d'affaires (€) | Résultat net (€) |
|---|---:|---:|
| 2024 | 12 381 245 | 2 689 219 |

## 7) Présence digitale
- Site web: https://www.octika.com
- Emails génériques: contact@octika.com

## 8) ICP, signaux et timing
- ICP: distributeurs B2B, retail optique, CA 5–20 M€
- Signaux: lancements de collections, pics saisonniers (rentrée), salons optique

## 9) Problématiques et opportunités
- Renouvellement rapide des collections, gestion de stocks multi-références, délais de réassort
- Activation commerciale omnicanale (opticiens indépendants vs chaînes)

## 10) Proposition de valeur ciblée
- Prévision et disponibilité réassort (objectif: -15–25% ruptures)
- Accélération sell-out en points de vente (+5–10% rotation)
- Outillage B2B (portail/EDI) pour réduire les temps de traitement (-30%)

## 11) Scripts multicanaux (rappel)
- Email (ouverture)
  Objet: Optimiser le réassort montures et l’activation opticiens
  Bonjour {Prénom}, nous aidons des distributeurs optique à réduire les ruptures (-20%) et accélérer la rotation en point de vente (+8%). 15 min pour voir si transposable chez OCTIKA ?

- Appel (ouverture)
  Contexte: distribution montures, enjeux réassort/activation. Proposition de 15 min pour audit flash.

- LinkedIn (accroche)
  Bonjour {Prénom}, vos enjeux réassort/activation chez OCTIKA m’intéressent. Partage d’un benchmark optique (10 pages) ?

## 12) Réseaux/liaisons utiles
- CAC titulaire partagé éventuel: CABINET PHS (SIREN 444175699) — à croiser sur d'autres prospects
- CAC suppléant: JP AUDIT (SIREN 795217256) — statut du cabinet à surveiller (dirigeant: Liquidateur)

## 13) Données structurées (JSON)
```json
{
  "siren": "435245170",
  "denomination": "OCTIKA",
  "statut": "A",
  "nature_juridique": { "code": "5710", "libelle": "SAS" },
  "date_creation": "2001-03-22",
  "categorie_entreprise": { "valeur": "PME", "annee": 2022 },
  "activite": { "ape": "46.43Z", "section": "G" },
  "etablissements": { "total": 2, "ouverts": 2 },
  "siege": {
    "siret": "43524517000012",
    "adresse": "121 Rue Georges Guynemer 34130 Mauguio",
    "commune_insee": "34154",
    "departement": "34",
    "region": "76",
    "epci": "243400470",
    "coordonnees": { "lat": 43.584785, "lon": 3.939612 },
    "effectifs": { "tranche_code": "12", "annee": 2022 },
    "idcc": ["0573"]
  },
  "dirigeance": {
    "president": {
      "type": "personne morale",
      "denomination": "FIVE VISION",
      "siren": "904391877",
      "activite": "70.10Z",
      "dirigeants": [
        {
          "type": "personne physique",
          "nom": "CINQUEGRANA",
          "prenoms": "STEFANO",
          "qualite": "Gérant",
          "date_naissance": "1968-07",
          "nationalite": "Italienne"
        }
      ]
    },
    "commissaires_aux_comptes": {
      "titulaire": { "denomination": "CABINET PHS", "siren": "444175699" },
      "suppleant": { "denomination": "JP AUDIT", "siren": "795217256" }
    }
  },
  "finances": { "2024": { "ca": 12381245, "resultat_net": 2689219 } },
  "contacts": { "site_web": "https://www.octika.com", "emails": ["contact@octika.com"] },
  "tags": ["34130", "CA_5_20M", "siege", "Distribution" ],
  "sources": [
    "API recherche-entreprises.data.gouv.fr (search?q=435245170 / 904391877 / 444175699 / 795217256)",
    "Fiche interne 435245170_OCTIKA.md"
  ]
}
```


