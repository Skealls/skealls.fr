---
title: "Déployer splunk dans Azure Cloud"
description: ""
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
menu:
  docs:
    parent: ""
    identifier: "example-6a1a6be4373e933280d78ea53de6158e"
weight: 810
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

Au sein de ce tutoriel, je vais tâcher d'expliquer comment monter un Splunk fonctionnel dans Azure Cloud.

## Intégrer Gitlab dans VSCode
### Générer une clé API

Pour commencer, on va devoir se générer une petite clé d'API Gitlab. Il faut ainsi se rendre dans :
- **Settings > Access Tokens**

Conservez la clé pour son utilisation future ! Aucune date d'expiration ne sera définie par défaut, à moins que vous ne le préfériez. Dans mon cas, je ne l'ai pas définie, car j'utilise toujours Gitlab pour mes projets personnels.

