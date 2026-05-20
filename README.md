# java-print-main

Minimal Maven app: `main` runs a single `System.out.println`.

## Build

```bash
mvn -q -DskipTests package
```

## Run

```bash
java -cp target/classes com.example.Main
```

On Windows PowerShell, paths use backslashes if you prefer: `java -cp target\classes com.example.Main`.
