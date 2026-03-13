Git Workflow Homework

## Rreth këtij projekti
Ky është një projekt për të praktikuar menaxhimin e historikut të Git. Gjatë punës, jam fokusuar në disa aspekte kryesore të Git si pastrimi i historikut, rikuperimi i commit-eve të humbura dhe menaxhimi i branch-eve.

## Çfarë është bërë?

Fillimisht u krijua repository dhe u shtua project.txt me disa commit-e të zakonshme si "update", "stuff" dhe "final changes". Më pas u bë një pastrim i historikut duke bashkuar disa prej commit-eve për të krijuar një histori më të pastër dhe kuptimplote.

Për të simuluar një gabim, u shtua një commit i ri dhe më pas u "humb" duke përdorur reset. Ky commit u rikuperua më pas duke përdorur reflog dhe u krijua një branch i ri (recovered-branch) pikërisht nga ai commit.

Për ta bërë më të lehtë shikimin e historikut, u krijua një alias që tregon historikun në formë grafike. Versioni i pastruar i projektit u tagua si v1.0.

Në fund, gjithçka u dërgua në GitHub duke përfshirë të dy branch-et dhe tag-un.

## Struktura

**Branch main** përmban versionin përfundimtar të pastruar:
- Version 1 of project
- Version 2 of project  
- Added some changes
- Final Version

**Branch recovered-branch** përmban të njëjtin kod por me një rresht shtesë që u rikuperua:
- Version 1 of project
- Version 2 of project
- Added some changes
- Final Version
- Temporary change that will be lost.
