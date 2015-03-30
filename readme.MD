
Generate project:

mvn -U archetype:generate -DarchetypeGroupId=com.springfuse.archetypes -DarchetypeArtifactId=quickstart -DarchetypeVersion=3.0.109 -DgroupId=com.sii.demo.wikifuse -Dpackage=com.sii.demo.wikifuse -DartifactId=wikifuse -Dversion=1.0.0 -DfrontEnd=backendJpa -Demail=ptrouillard@sii.fr -Dpassword=none -DjdbcGroupId=postgresql -DjdbcArtifactId=postgresql -DjdbcVersion=8.2-504.jdbc3 -DjdbcDriver=org.postgresql.Driver -DjdbcUser=sii -DjdbcPassword=sii -DjdbcUrl=jdbc:postgresql://localhost/wikifuse -DinteractiveMode=false -DarchetypeRepository=http://maven2.springfuse.com/ 
cd wikifuse

Generate code:

mvn -f springfuse.xml generate-sources
