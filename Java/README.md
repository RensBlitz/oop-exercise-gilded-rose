# Gilded Rose starting position in Java

## Running Tests

### Run JUnit Tests

```
./gradlew test
```

Or with Maven:

```
mvn test
```

### Run Manual Test Fixture

The `TexttestFixture` class provides a simple way to manually verify the code by running it with sample items and viewing the output:

```
./gradlew text
```

To specify the number of days to simulate (e.g., 10 days):

```
./gradlew text --args "10"
```

This will print the inventory state for each day, showing how items change over time.
