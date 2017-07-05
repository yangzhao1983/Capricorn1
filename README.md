# Capricorn1
New version of Capricorn. Build with gradle, a much stronger tool than ant and maven.

# to get the jars for Dev/Debug
1. Add new task copyJars
 
 29 task copyJars(type:Copy){
 30         from configurations.runtime
 31         into '$LOCAL_DIR'
 32 }
 
2. Run 'gradle copyJars'
3. Lib list
commons-codec-1.10.jar		curvesapi-1.04.jar		poi-ooxml-3.15.jar		stax-api-1.0.1.jar
commons-collections4-4.1.jar	poi-3.15.jar			poi-ooxml-schemas-3.15.jar	xmlbeans-2.6.0.jar

# to build the project
Run 'gradle build'

# POI doc
https://poi.apache.org
