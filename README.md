# ZIP 

![Maven](https://img.shields.io/maven-central/v/com.github.rillis/zip)
![License](https://img.shields.io/github/license/rillis/zip)

```xml
<dependency>
  <groupId>com.github.rillis</groupId>
  <artifactId>zip</artifactId>
  <version>1.0.0</version>
</dependency>
```

## Docs

**Methods:**  
```java
//Zip multiple files/folders. Returns .zip file itself.
com.github.rillis.Zip.zip(File[] fileToZip, File finalZipFile) : File  
throws FileNotFoundException, IOException.

//unimplemented
com.github.rillis.Zip.unZip()
```

**Config:**  
```java
//Buffer size
int com.github.rillis.Zip.BUFFER_SIZE
```