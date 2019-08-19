### primefaces
---
https://github.com/primefaces/primefaces

https://www.primefaces.org/

```java
// primefaces/src/test/java/org/primefaces/mock/pf/PrimeConfigurationMock.java

public class PrimeConfigurationMock extends PrimeConfiguration {
  
  private boolean validateEmptyFields = false;
  private boolean partialSubmitEnabled = false;
  
  private boolean stringCoverterAvailable = false;
  
  private Map<String, String> errorPages = null;
  
  public PrimeConfigurationMock(FaceContext context, PrimeEnvironment environment) {
    super(context, environment);
  }
  
  
  
}
```

```sh
xmlns:p="http://primefaes.org/ui"
```

```
```


