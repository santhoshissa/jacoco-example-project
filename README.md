##Output

	----
	Commit: caaa32f8c8eff580b4760f60dbf021d6e03935c3 - Sun Jul 16 20:48:50 AEST 2017 - Julian Gamble - [dev] first drop

	source file name: /com/machiavellian/MyApplication.java
	Intersection of line changes with coverage (lines we care about): 4
	covered lines: 3
	Coverage for commit: 75%
	Lines not covered: 1
	src/main/java/com/machiavellian/MyApplication.java:11         return firstArg - secondArg;

	----
	Commit: 57bfb7956b501afca5fc101753d6e284d448f4ce - Sun Jul 16 20:53:59 AEST 2017 - Julian Gamble - [dev] adding new method

	Intersection of line changes with coverage (lines we care about): 1
	covered lines: 1
	Coverage for commit: 100%
	Lines not covered: 0
	----
	Commit: acf35680891d1f853a226035981c1ac18d9f50a2 - Sun Jul 16 20:55:58 AEST 2017 - Julian Gamble - [dev] adding coverage

	Intersection of line changes with coverage (lines we care about): 0
	covered lines: 0
	Coverage for commit: 0%
	Lines not covered: 0
	----
	Commit: 9c42a1ab1e8db57e31e17837120da6dc257dbb72 - Sun Jul 16 20:56:23 AEST 2017 - Julian Gamble - [dev] adding divide method

	Intersection of line changes with coverage (lines we care about): 1
	covered lines: 0
	Coverage for commit: 0%
	Lines not covered: 1
	src/main/java/com/machiavellian/MyApplication.java:19         return firstArg / secondArg;

	----



##Running

mvn clean test


##New Report

    target/site/jacoco-ut/coverage-per-commit.txt