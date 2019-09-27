# SampleLib
demo

For gradle--
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.krishan3421:SampleLib:1.1'
	}

For maven--

Step 1. Add the JitPack repository to your build file

	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>


Step 2. Add the dependency

	<dependency>
	    <groupId>com.github.krishan3421</groupId>
	    <artifactId>SampleLib</artifactId>
	    <version>Tag</version>
	</dependency>