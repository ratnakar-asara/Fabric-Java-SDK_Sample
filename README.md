Pre-reqs for [Fabric Java SDK](https://github.com/hyperledger/fabric-sdk-java)

----------------------------------------------------------------

## [How to install Java SDK 1.8 ](http://tecadmin.net/install-oracle-java-8-jdk-8-ubuntu-via-ppa/#) on Ubuntu 14.04

### Installation:
```
	sudo add-apt-repository ppa:webupd8team/java
	sudo apt-get update
	sudo apt-get install oracle-java8-installer
```

### Verify Installation
```
	java -version
```

### Configure Java Environment:

```
	sudo apt-get install oracle-java8-set-default
```

## [How to install maven](https://www.mkyong.com/maven/how-to-install-maven-in-ubuntu/) :

### Installation command
```
	sudo apt-get install maven
```

### Verify Installation
```
	mvn -version
```
----------------------------------------------------------------

Couldn't get pass through the below step :-(

```mvn test``` 

OR 

```mvn install```

Awaiting for the JIRA issue [FAB-907](https://jira.hyperledger.org/browse/FAB-907)
