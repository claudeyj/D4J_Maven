# Configured Maven projects for Defects4J 1.2 programs

Sometimes we need a configured Defects4J repository to facillitate the use of maven plugins. https://github.com/lx0704/Defects4J-Maven is configured for that purpose (please read that README first). However, part of the repo (Defects4J 1.2 dataset) was configured too earlier that some source files have been outdated. So this repo reconfigured the programs to mitigate the gap. The source files are consistent with the latest (and stable) version of the Defects4J programs. The "Repository" contains most of the required dependencies (directly copied from lx0704 version). Please copy all the dependencies to the .m2 folder.

If you still find some dependencies missing (or connection to repository server timing out), please first check the local folders, e.g., "lib", to obtain the required jar file, and use "mvn install-file" command to install the jar file to local.

If you find some programs showing different result with defects4j command, please report the issues.
