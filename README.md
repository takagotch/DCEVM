### dcevm
---
https://dcevm.github.io/

```java
// agent/src/main/java/com/github/dcevm/agent/InstrumentationAgent.java

public class InstrumentationAgent {
  public static Instrumentation INSTRUMENTAION;
  
  public static void agentmain(String args, Instrumentation instr) {
    INSTRUMENTATION = instr;
  }
  
  public static void premain(String args, Instumentation instr) {
    INSTRUMENTATION = instr;
  }
}
```

```
```

```
```


