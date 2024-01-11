## Welcome! 🥳

This data approach **student achievement** in secondary education of **two Portuguese schools**. The data attributes include **student grades, demographic, social and school** related features and it was collected by using school reports and questionnaires. 

Two datasets are provided regarding the performance in two distinct subjects: **Mathematics (mat.csv) and Portuguese language (por.csv)**. In [Cortez and Silva, 2008], the two datasets were modeled under binary/five-level classification and regression tasks.

## Dataset Description

#### Attributes for both **student-mat.csv** (Math course) and **student-por.csv** (Portuguese language course) datasets:

| Variable | Description |
| --- | --- |
| `school` | student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira) |
| `sex` | student's sex (binary: 'F' - female or 'M' - male) |
| `age` | student's age (numeric: from 15 to 22) |
| `address` | student's home address type (binary: 'U' - urban or 'R' - rural) |
| `famsize` | family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3) |
| `Pstatus` | parent's cohabitation status (binary: 'T' - living together or 'A' - apart) |
| `Medu` | mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education) |
| `Fedu` | father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education) |
| `Mjob` | mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other') |
| `Fjob` | father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other') |
| `reason` | reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other') |
| `guardian` | student's guardian (nominal: 'mother', 'father' or 'other') |
| `traveltime` | home to school travel time (numeric: 1 - &lt;15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - &gt;1 hour) |
| `studytime` | weekly study time (numeric: 1 - &lt;2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - &gt;10 hours) |
| `failures` | number of past class failures (numeric: n if 1&lt;=n&lt;3, else 4) |
| `schoolsup` | extra educational support (binary: yes or no) |
| `famsup` | family educational support (binary: yes or no) |
| `paid` | extra paid classes within the course subject (Math or Portuguese) (binary: yes or no) |
| `activities` | extra-curricular activities (binary: yes or no) |
| `nursery` | attended nursery school (binary: yes or no) |
| `higher` | wants to take higher education (binary: yes or no) |
| `internet` | Internet access at home (binary: yes or no) |
| `romantic` | with a romantic relationship (binary: yes or no) |
| `famrel` | quality of family relationships (numeric: from 1 - very bad to 5 - excellent) |
| `freetime` | free time after school (numeric: from 1 - very low to 5 - very high) |
| `goout` | going out with friends (numeric: from 1 - very low to 5 - very high) |
| `Dalc` | workday alcohol consumption (numeric: from 1 - very low to 5 - very high) |
| `Walc` | weekend alcohol consumption (numeric: from 1 - very low to 5 - very high) |
| `health` | current health status (numeric: from 1 - very bad to 5 - very good) |
| `absences` | number of school absences (numeric: from 0 to 93) |



#### these grades are related with the **course subject**, Math or Portuguese:


`G1` - first period grade (numeric: from 0 to 20)
`G2` - second period grade (numeric: from 0 to 20)
`G3` - final grade (numeric: from 0 to 20, output target)
