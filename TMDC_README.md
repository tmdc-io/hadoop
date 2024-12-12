# command to rebuild jar of haddop-client-runtime
```shell
git checkout hadoop-3.3.6-vulnerabilities_fixes
cd hadoop-client-modules/hadoop-client-runtime
```
# Only build hadoop-client-runtime jar
```shell
mvn clean install -DskipTests=true
```
# Copy jar from below location
```shell
hadoop-client-modules/hadoop-client-runtime/target/hadoop-client-runtime-3.3.6.jar
```