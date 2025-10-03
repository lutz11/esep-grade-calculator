# ESEP Grade Calculator

This library is a simple utility to calculate your grades. Assignments are weighted 50%, exams 35%, and essays 15%, with grades corresponding to A (90+), B(80+), C (70+), D (60+), and F (below 60).

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

Files:
```
grade_calculator.go - Where the main logic for the calculator lies, including its structs
grade_calculator_test.go - Unit tests
```