<<<<<<< HEAD
# FleetCheck – Build Systems Lab

This project is intentionally incomplete. Follow the worksheet in the order given.

Expected final application output:

```
FleetCheck 1.0
Vehicles loaded: 4
Vehicles requiring service: 2
Average mileage: 37000 km
```

Do not copy the solution POM. The objective is to observe how each build change alters the result.

Relevant error :[ERROR] /C:/Users/andre/Desktop/3º Ano - 1º Semestre/Qualidade de software/w4/FleetCheck_Starter/FleetCheck_Starter/src/main/java/pt/upt/fleetcheck/App.java:[4,38] package com.fasterxml.jackson.databind does not exist

APP Java : package com.fasterxml.jackson.databind

Question: Why is this a better failure than the one from Step 1?
    The code is syntacticlly correct and we pass the compilation phase failing only in the test phase 

Evidence 4: Explain what the Shade plugin changed compared with the default JAR.
   without the plugin, mvn produces only fleetcheck-1.0.0.jar, with has no Main-Class, with the plugin, the build produces an executable, self-contained JAR, fleetcheck-1.0.0-all.jar
=======
# Worksheet4
>>>>>>> be5a16de8b09eaa189db4230886d642ae070b327
