# Politique de sécurité

> 🇬🇧 **English version below:** [Security policy](#security-policy)

## Signaler une vulnérabilité

Les vulnérabilités touchant les systèmes des ministères et organismes publics québécois se signalent sur la **[plateforme de signalement de vulnérabilités](https://www.cyber.gouv.qc.ca/signalements/signalement-vulnerabilites)** du Centre gouvernemental de cyberdéfense (CGCD).

- N'ouvrez **pas** d'issue ni de pull request publique pour signaler une vulnérabilité.
- Les signalements sont encadrés par les [conditions d'utilisation](https://www.cyber.gouv.qc.ca/signalements/conditions-utilisation).
- Le [programme de prime aux bogues](https://yeswehack.com/programs/programmes-de-primes-aux-bogues-du-gouvernement-du-quebec-cgcd), sur YesWeHack, récompense les failles trouvées de manière éthique dans sa portée.
- Les personnes qui contribuent sont remerciées sur la [page des contributeurs](https://www.cyber.gouv.qc.ca/signalements/contributeurs).
- Contact lisible par machine : [`security.txt`](https://www.cyber.gouv.qc.ca/.well-known/security.txt).

## CERT-QC

Le CERT-QC est l'équipe d'intervention en cas d'incident (CERT) du gouvernement du Québec, portée par le CGCD. Il coordonne les incidents de sécurité de portée gouvernementale et dessert les organismes publics assujettis à la LGGRI.

- **Courriel :** certqc@cyber.gouv.qc.ca
- **Clé PGP :** [`CERT-QC_0x2329D025_public.asc`](https://www.cyber.gouv.qc.ca/publications/CERT-QC_0x2329D025_public.asc) (ed25519, expire le 2028-02-17)
- **Empreinte :** `9729 3E46 E0E5 E8EE 46BD  A427 8151 A934 2329 D025`
- **RFC 2350 :** [description du CERT-QC](https://www.cyber.gouv.qc.ca/publications/DOC_RFC_2350.pdf)

Vérifiez l'empreinte avant d'utiliser la clé :

```sh
curl -sO https://www.cyber.gouv.qc.ca/publications/CERT-QC_0x2329D025_public.asc
gpg --show-keys --with-fingerprint CERT-QC_0x2329D025_public.asc
```

---

# Security policy

## Reporting a vulnerability

Vulnerabilities affecting the systems of Québec government departments and public bodies are reported on the **[vulnerability reporting platform](https://www.cyber.gouv.qc.ca/en/report/vulnerability-report-platform)** of the Centre gouvernemental de cyberdéfense (CGCD).

- Do **not** open a public issue or pull request to report a vulnerability.
- Reports are governed by the [conditions of use](https://www.cyber.gouv.qc.ca/en/report/conditions-of-use).
- The [bug bounty program](https://yeswehack.com/programs/programmes-de-primes-aux-bogues-du-gouvernement-du-quebec-cgcd), on YesWeHack, rewards flaws found ethically within its scope.
- Contributors are acknowledged on the [contributors page](https://www.cyber.gouv.qc.ca/en/report/contributors).
- Machine-readable contact: [`security.txt`](https://www.cyber.gouv.qc.ca/.well-known/security.txt).

## CERT-QC

CERT-QC is the Computer Emergency Response Team of the Government of Québec, run by the CGCD. It coordinates government-wide security incidents and serves the public bodies subject to the LGGRI (Québec's act on the governance and management of information resources).

- **Email:** certqc@cyber.gouv.qc.ca
- **PGP key:** [`CERT-QC_0x2329D025_public.asc`](https://www.cyber.gouv.qc.ca/publications/CERT-QC_0x2329D025_public.asc) (ed25519, expires 2028-02-17)
- **Fingerprint:** `9729 3E46 E0E5 E8EE 46BD  A427 8151 A934 2329 D025`
- **RFC 2350:** [CERT-QC description](https://www.cyber.gouv.qc.ca/publications/DOC_RFC_2350.pdf) (in French)

Check the fingerprint before using the key:

```sh
curl -sO https://www.cyber.gouv.qc.ca/publications/CERT-QC_0x2329D025_public.asc
gpg --show-keys --with-fingerprint CERT-QC_0x2329D025_public.asc
```
