# ai-lab-engel1-pakkeliste
Liste med python-pakker som skal sluses inn eller er slust inn til Engel 1 via intern nexus server. Dette for å muliggjøre kontinuerlig sårbarhetsvurdering av kodeverk slik beskrevet her: https://confluence.adeo.no/pages/viewpage.action?pageId=259099058.

### Fremgangsmåte:
Når en ny python pakke ønskes tilgjengeliggjort på Engel1, skal avhengighetene (hentet fra f.eks. "requirements.txt" filen til pakken) legges til requirements.txt filen her.
Fullstendig fremgangsmåte finnes her: https://confluence.adeo.no/x/USYTEw
Pakkene i sistnevnte fil vil da vurderes og monitoreres av githubs "security vulnerability" (https://help.github.com/en/articles/about-security-alerts-for-vulnerable-dependencies) og SNYK.

