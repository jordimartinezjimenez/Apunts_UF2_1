# Apunts_UF2_1

# ENTORNS DE DESENVOLUPAMENT

## Proves de software
Conjunt de processos amb els quals es pretén provar el sistema o aplicació en diferents moments per comprovar el seu correcte funcionament.
### Objectius de les proves
  - Provar si el programari no fa el que ha de fer
  - Provar si el programari fa el que no ha de fer.  
### Forma de les proves
  - **Proves dinàmiques:** Requereixen l'execució de l'aplicació. Permeten mesurar el comportament de l'aplicació desenvolupada.
  - **Proves estàtiques:** Es realitzen sense executar el codi de l'aplicació. S'examina el codi font.  

### Estratègies de prova
  - **Caixa negra:** S'estudia el sistema des de fora. Són proves de funcionalitat.
    - S'estudia el sistema des de fora.
    - Es treballa sobre la interfície.
    - No es tenen en compte els detalls interns de funcionament.
    - Es proporcionen entrades i s'estudien les sortides.
    - Principals tècniques:
        - Particions d'equivalència
        - Valors límit  
        <img src="https://user-images.githubusercontent.com/74070913/106040110-431c5780-60da-11eb-914f-7e2ab12baf3c.png" alt="Caixa-negra" width="250"/>  

  - **Caixa blanca:** S'examina el codi font i la seva execució. Són proves estructurals.
    - S'examina el codi font i la seva execució.
    - Es comproven els fluxos d'execució dins de cada unitat (funció, classe, mòdul, etc.)
    - També poden comprovar els fluxos entre unitats durant la integració.
    - I fins i tot entre subsistemes, durant les proves de sistema.
    - Principals tècniques:
        - Cobertura de codi
        - Prova de bucles
        <img src="https://user-images.githubusercontent.com/74070913/106040316-91315b00-60da-11eb-823c-1a12bd003dc7.png" alt="Caixa-blanca" width="250"/>

### Tipus de proves
  - Funcionals: Avaluen el compliment dels requisits.
    - Proves unitàries (o d'unitat)
    - Proves de regressió
    - Proves d'integració
    - Proves de fum (proba de foc)
    - Proves de sistema
    - Proves alfa i beta
    - Proves d'acceptació (validació per part de client)
  - No funcionals: Avaluen aspectes addicionals com rendiment, seguretat...
    - Proves d'usabilitat
    - Proves de rendiment
    - Proves d'estrés
    - Proves de seguretat
    - Proves de compatibilitat
    - Proves de portabilitat
### Mecanismes de proves
  - **Manual:** Mitjançant proves realitzades per personal de l'empresa o extern.
  - **Automàtic**: Mitjançant programari que executa codi de forma automatitzada i compara els resultats obtinguts i els resultats esperats.
## Frameworks
És una estructura de conceptes, pràctiques, biblioteques, etc ... que serveix de base per a organitzar i desenvolupar un programari.
Està compost per:
  - Un conjunt de les millors pràctiques i suposicions
  - Eines comunes
  - Biblioteques  
Permet unificar el procés de desenvolupament entre desenvolupadors.
Ex: 
  - Java: JUnit, TestNG
  - C++: CppUnit, Google Test
  - PHP: PHPUnit
  - Javascript: Mocha

## Integració
### Formes d'integració
  - Integració del Big Bang
  - Integració descendent
  - Integració ascendent
  - Integració contínua (CI)

### Servidors d'integració continua
**CI:** Integració contínua  
**CD:** Lliurament contínua
  - Jenkins  <img src="https://user-images.githubusercontent.com/74070913/106042383-449b4f00-60dd-11eb-90cc-175e48c98153.png" alt="Jenkins-Logo" width="50"/>
  - Bamboo  <img src="https://user-images.githubusercontent.com/74070913/106042578-85936380-60dd-11eb-8dfa-65a4cae63ede.png" alt="Bamboo-Logo" width="50"/>
  - TravisCI  <img src="https://user-images.githubusercontent.com/74070913/106042625-98a63380-60dd-11eb-9dfd-90e342ad93b9.png" alt="Jenkins-Logo" width="50"/>
  - CircleCI  <img src="https://user-images.githubusercontent.com/74070913/106042647-a22f9b80-60dd-11eb-8bdb-cb962067b723.png" alt="Jenkins-Logo" width="50"/>

## Qualitat
**QA:** Calidad del proceso  
**QC:** Calidad del producto  
QA garantiza la calidad en los procesos mediante los cuales se desarrollan los productos y QC garantiza la calidad de los productos centrándose en identificar defectos en los productos reales producidos.

### Factors de qualitat
  - Operació de l'producte
     - Correcció: el programari compleix les especificacions
     - Fiabilitat: grau en què el programari és fiable
     - Eficiència: necessitat de recursos software i hardware del producte
     - Seguretat: grau en el qual pot controlar l'accés a l'programari i a les dades
     - Facilitat d'ús: grau d'esforç necessari per utilitzar el programari
  - Revisió del producte
    - Mantenibilitat: esforç requerit per localitzar i reparar un error
    - Flexibilitat: esforç necessari per modificar un programa
    - Facilitat de prova: esforç requerit per a realitzar les proves d'un programa
  - Transició del producte
     - Portabilitat: facilitat per migrar el programari d'un entorn d'operació a un altre
     - Reusabilitat: grau en el qual un programa o part d'aquest es pot utilitzar en altres aplicacions
     - Interoperativitat: esforç necessari perquè un programari operi conjuntament amb altres sistemes
