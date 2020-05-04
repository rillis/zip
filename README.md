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

**Methods:**  
```java
//Zip multiple files/folders. Returns .zip file itself.
com.github.rillis.Zip.zip(File[] fileToZip, File finalZipFile) : File  
throws FileNotFoundException, IOException.

//Unzip to destination folder, create folder if it doesn't exists. Returns destFolder. 
com.github.rillis.Zip.unZip(File zipFile, File destFolder) : File
throws FileNotFoundException, IOException.
```

**Config:**  
```java
//Buffer size
int com.github.rillis.Zip.BUFFER_SIZE
```