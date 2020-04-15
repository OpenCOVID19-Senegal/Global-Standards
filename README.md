# Global-Standards
Dans le domaine de la santé, il est crucial de respecter les normes et standards quand il s'agit de fournir des applications/outils. Se conformer aux standards permet une interoperabilité entre applications, ce qui réduit la fracture numérique de nos outils mais aussi la redondance des initiatives et ainsi favoriser la complémentarité entre outils.

I- Qu'entend-on par normes et standards?
Les normes et standards sont mis en place pour faciliter le travail des fournisseurs au moment de la conception de leur(s) solution(s), mais aussi de pouvoir faciliter l'interopérabilité entre applications que ca concerne les acteurs externes ou le ministère de la santé (MoH).

Nous remarquons plein d'applications qui font la même chose mais sont incapables de s'échanger des données dans le but d'appuyer le MoH. Certains fournisseurs se voient obliger de faire un travail préalable pour assurer un partage/échange de données.
Plein de frameworks existent pour faciliter cet echange de données plus connu sous le nom anglissisme de Health Information Exchange (HIE)

Je partagerai quelques tips/links utiles pour s'informer sur les standards les plus connus, beaucoup plus utilisés dans la zone Anglophone.

II- Exemples
  1) FHIR (Fast Healthcare Interoperability Resources) - prononcez "fire"(feu)
    Standard décrivant des formats de données et des éléments ainsi qu'une interface de programmation applicative pour les échanges d'informations dans le domaine de la santé.
    FHIR est développé par HL7 (health Level 7) qui est une organisation à but non lucratif dédiée au développement de l'interopérabilité des données de santé et la standardisation du protocole d'échanges médicaux.
    Le principal domaine d'intervention de FHIR est donc le "dossier médical partagé".
    Il vous decrit/liste les informations utiles pour une resource donnée (patient, service de santé, etc...)
    Exemple 1: La resource Patient: decrit comme etant toute info administrative ou demographique sur un individu/animal recevant des soins ou des prestations de service de santé
  Donc les infos du patinet sont 
    identifiant
    active
    name
    telecom
    gender
    .....
   
    
   Exemple2: Service de santé
    ...
    
