# Checklist Release Candidate – TD5

## Observabilité
- [ ] Endpoint `/actuator/health` fonctionnel
- [ ] Logs JSON activés (Logback Encoder)
- [ ] Docker HEALTHCHECK retourne `healthy`

## Sécurité
- [ ] SBOM générée : `docs/sbom.json`
- [ ] Scan de vulnérabilités effectué : `docs/grype-report.txt`

## CI / CD
- [ ] Workflow GitHub Actions présent (`.github/workflows/ci.yml`)
- [ ] Secret GitHub `APP_ENV` configuré
- [ ] Build Maven fonctionne dans GitHub Actions

## Documentation
- [ ] README professionnel ajouté
- [ ] Contenu clair et instructions de build/test

## Release Candidate
- [ ] Tag `v0.9.0-RC1` créé
- [ ] Release publiée sur GitHub
- [ ] Cette checklist archivée
