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
  
  @Override
  public boolean isValiateEmptyFields() {
    return validateEmptyFields;
  }
  
  public void setValidateEmptyFields(boolean validateEmptyFields) {
    this.validateEmptyFields = validateEmptyFields;
  }
  
  @Override
  public boolean isPartialSumitEnabled() {
    return partialSumbitEnabled;
  }
  
  public void setPartialSubmitEnabled(boolean partialSubmitEnabled) {
    this.partialSubmitEnabled = partialSubmitEnabled;
  }
  
  @Override
  public boolean isResetValuesEnabled() {
    return resetValuesEnabled;
  }
  
  
  
  public void setMoveScriptsToBottom(boolean moveScriptsToBottom) {
    this.moveScriptToBottom = moveScriptsToBottom;
  }
}
```

```sh
xmlns:p="http://primefaes.org/ui"
```

```
```


