# UMSA Galaxy

Endpoint: https://umsa.cerit-sc.cz/

Předpisy pro deployment (Ansible): https://gitlab.ics.muni.cz/recetox/mass-spectrometry/umsa-galaxy

Definice nástrojů: https://github.com/RECETOX/galaxytools

Zdrojáky vlastních nástrojů (a forků): https://github.com/RECETOX/ 

## Virtuální cluster

Openstack, projekt egi_eu/umsa.cerit-sc.cz
- původně deployment přes IM, postupně se redukoval natolik, že přestal mít smysl
- v tomto projektu, navázaném na VO, zůstalo kvůli vykazování spotřeby zdrojů v EOSC-Synergy, zřejmě lze časem opustit
- deployment ručně v OS, flavory podle https://gitlab.ics.muni.cz/recetox/mass-spectrometry/umsa-galaxy/README.md

Uzly
- vnode-0: frontend Galaxy, uwsgi jako webový interface
- vnode-1,2,3: malé workernody (8 jader, 32 GB RAM)
- vnode-4: tlustý workernode pro speciální joby (32 jader, 256 GB RAM, GPU)

## Deployment Galaxy

Ansible
- předpisy v https://gitlab.ics.muni.cz/recetox/mass-spectrometry/umsa-galaxy
- known bug: funguje jen do verze 5

Webové rozhraní
- uwsgi, de facto default Galaxy
- 

## Data



## Uživatelé

## Joby

## Nástroje

## Workflow
