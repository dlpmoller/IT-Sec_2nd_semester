# IT-Sec_2nd_semester
Software Security module
---
**Dette er et skole-projekt**
*Unit tests:*
---
![Hvad der skulle testes](<unit tests.PNG>)
![Hvad resultatet var](<unit test result.PNG>)
---
*Test teknikker:*
|Navn|Område|Beskrivelse|Gate|
|-|-|-|-|
|Ækvivalensklasser|Identity & Access Management|Grupperer forskellige roller sammen for en uniform adgangskontrol|System|
|Grænseværdi|Password kontrol|Sørger for en rimelig samling af entropy-bits at komme igennem|Development|
|CRUD(L)|Identity & Access Management|Tilladelsesmatrix der i sammenhæng med ækvivalensklasser let kan skabe roller som f.eks. kun kan læse information, eller kan se listen over data|System|
|Cycle Process Test|Plan, Do, Check, Act|Ved at have en kontinuerlig cyklus af justering, test og analyse af testresultater, kan der skabes en positiv udvikling af sikkerhedsanordninger i en given organisation|Release Candidate|
|Testpyramide|DevSecOps|[Selv ubetydelige forsinkelser og forstyrrelser i drift kan være advarselssignaler](https://www.theguardian.com/commentisfree/2024/apr/06/xz-utils-linux-malware-open-source-software-cyber-attack-andres-freund)|Integration|
|Decision Table|Identity & Access Management|Dette er meget hen ad vejen hvad en IAM løsning er. Hvilken handling (CRUDL) kigger denne rolle efter?| System