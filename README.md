# ZIP 

![Maven](https://img.shields.io/maven-central/v/com.github.rillis/zip)
![License](https://img.shields.io/github/license/rillis/zip)

```xml
<dependency>
  <groupId>com.github.rillis</groupId>
  <artifactId>zip</artifactId>
  <version>1.1.0</version>
</dependency>
```

## Docs

**Classes:** 
com.github.rillis.Zip  

**Methods:**  
```java
//Zip multiple files/folders. Returns .zip file itself.
Zip.zip(File[] fileToZip, File finalZipFile) : File  
throws FileNotFoundException, IOException.

//Unzip to destination folder, create folder if it doesn't exists. Returns destFolder. 
Zip.unZip(File zipFile, File destFolder) : File
throws FileNotFoundException, IOException.
```

**Config:**  
```java
//Buffer size
int Zip.BUFFER_SIZE
```