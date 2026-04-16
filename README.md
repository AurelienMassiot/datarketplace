# Datarketplace

Le shop le plus cool du recrutement. Gagne des OCTOcoins en participant aux actions de recrutement et dépense-les sur des récompenses.

## Déploiement

Le site est hébergé sur **GitHub Pages** et se déploie automatiquement à chaque push sur `main`.

**URL de production :** https://aurelienmassiot.github.io/datarketplace/

### Déployer une mise à jour

```bash
git add index.html
git commit -m "votre message"
git push origin main
```

Le déploiement est effectif en quelques secondes. Pas de build, pas de dépendances — le site est un fichier HTML statique unique.

### Vérifier le statut du déploiement

```bash
gh api repos/AurelienMassiot/datarketplace/pages --jq '.status'
```
