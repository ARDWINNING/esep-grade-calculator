# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

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
Structure:
a.	README.MD: Documentation
b.	go.mod: Declares the public modules & dependencies (none)
c.	grade_calculator.go: The operating code for the grade calculator
d.	grade_calculator_test.go: The tests for the grade calculator

## Usage

- Start a new instance with NewGradeCalulator()
- Add all grades for Assignment, Exam, Essay with AddGrade(descr, score, type)
- Use GetFinalGrade() to get the letter grade