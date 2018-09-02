# gradleでproguardを使う方法

## Java9以降
Java9以降ではrt.jar等がないので下記を使用する
```
    libraryjars files(             "${javaHome}/jmods/java.base.jmod"  // Java SEランタイム     )
```
