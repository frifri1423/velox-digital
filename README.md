# 🚀 Déploiement — Velox Digital

## Option 1 — GitHub Pages (Gratuit, recommandé)

### Étape 1 : Créer un repo GitHub
1. Allez sur https://github.com et créez un compte (si pas déjà fait)
2. Cliquez sur "New repository"
3. Nommez-le `velox-digital`
4. Mettez-le en "Public"
5. Cliquez "Create repository"

### Étape 2 : Pousser le site (2 minutes)

Sur votre machine, exécutez ces commandes :

```bash
# Cloner le repo localement (remplacez par l'URL de votre repo)
git clone https://github.com/[VOTRE-USERNAME]/velox-digital.git
cd velox-digital

# Copier le contenu du site dans le repo
cp /home/ubuntu/.openclaw/workspace/business/site/index.html .

# Pousser sur GitHub
git add index.html
git commit -m "Site Velox Digital v1"
git push origin main
```

### Étape 3 : Activer GitHub Pages
1. Dans votre repo → Settings → Pages
2. Source : "Deploy from a branch" → "main" → "/ (root)"
3. Cliquez "Save"

**Votre site sera en ligne sur :** `https://[VOTRE-USERNAME].github.io/velox-digital`

---

## Option 2 — Netlify (Gratuit, encore plus simple)

1. Allez sur https://app.netlify.com/drop
2. Glissez-déposez le fichier `index.html`
3. C'est fait — vous obtenez une URL temporaire
4. Pour un domaine personnalisé : achetez `veloxdigital.fr` sur Gandi et connectez-le à Netlify

---

## Option 3 — Hébergement classique (pour veloxdigital.fr)

1. Achetez le domaine sur Gandi (~10€/an)
2. Dans Netlify : Site Settings → Domain Management → Add custom domain
3. Configurez les DNS comme indiqué par Netlify

---

## Configuration email (GRATUIT)

Pour avoir `contact@veloxdigital.fr` sans payer de serveur :

**Option : Brevo (gratuit jusqu'à 300 emails/jour)**
1. Créez un compte sur https://app.brevo.com
2. Ajoutez votre domaine `veloxdigital.fr`
3. Créez une adresse `contact@veloxdigital.fr`
4. Configurez le MX dans vos DNS Gandi

---

## Formulaire de contact

Le formulaire est déjà configuré avec Formspree.
Pour le rendre fonctionnel :
1. Créez un compte gratuit sur https://formspree.io
2. Créez un nouveau formulaire
3. Copiez votre Form ID (remplacez `xpwzgvnk` dans le HTML par votre ID)

---

## Prochaine étape après mise en ligne

1. Partagez le site à vos proches pour valider
2. Commencez la prospection LinkedIn (cf. `business/scripts/prospection-linkedin.md`)
3. Lisez le plan de lancement : `business/ops/plan-lancement-30j.md`
