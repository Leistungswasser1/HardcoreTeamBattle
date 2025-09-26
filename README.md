[README.txt](https://github.com/user-attachments/files/22566372/README.txt)

HardcoreTeamBattle - Plugin (source)
===================================

This project contains a basic Paper/Spigot plugin source for the Hardcore Team Battle mode.

Files included:
 - src/main/java/.../HardcoreTeamBattle.java
 - src/main/resources/plugin.yml
 - pom.xml
 - .github/workflows/build.yml (GitHub Actions to build automatically)

Build options:
1) Local (recommended):
   - Install Java 17 and Maven.
   - Run: mvn clean package
   - Result: target/*.jar

2) GitHub (no local setup):
   - Push this repository to GitHub on branch 'main' and run the workflow (Actions tab).
   - Download the artifact from the workflow run.

Upload to Nitrado:
 - Panel -> Files -> minecraft/plugins -> Upload .jar
 - or use FTP to upload to /minecraft/plugins/
 - Restart server from panel.

Notes:
 - If you don't have Maven/Java locally, use the GitHub Actions workflow to build the jar automatically.
 - If the environment where this notebook runs does not have Maven/Java, this README and the zip will help you build it elsewhere.
