mvn archetype:generate -DarchetypeGroupId=io.openliberty.tools -DarchetypeArtifactId=liberty-archetype-webapp -DarchetypeVersion=3.1 -DgroupId=com.orebmann -DruntimeVersion=19.0.0.11 -DartifactId=helloLiberty -Dversion=1.0-SNAPSHOT

mvn archetype:generate -DarchetypeGroupId=io.openliberty.tools -DarchetypeArtifactId=liberty-archetype-mp -DarchetypeVersion=3.1 -DgroupId=com.orebmann -DruntimeVersion=19.0.0.11 -DartifactId=hellomp -Dversion=1.0-SNAPSHOT

mvn archetype:generate \
    -DarchetypeGroupId=io.openliberty.tools \
    -DarchetypeArtifactId=liberty-archetype-mp \
    -DarchetypeVersion=2.3-SNAPSHOT \
    -DgroupId=test \
    -DartifactId=test \
    -Dversion=1.0-SNAPSHOT