# Technical Interview Prompts

## Python

### Prompt #1:
Write a Python script that converts a list into a dict, where the dict key for each item is the index number in the list.
```
EXAMPLE: $ ./script.py
         | Original List: [111, 'two', 333, 'four', {'five': 555}]
         | New Dictionary: {0: 111, 1: 'two', 2: 333, 3: 'four', 4: {'five': 555}}
```
### Prompt #2:
Write a Python script that calculates each student's average score using the below dictionary as the source of the input data:
```
Example: $ ./script.py
         | Sally: 88
         | Grace: 89
         | Tom: 90
```
```
data = {"Tom":{"tests":{"2021-02-01":89,"2021-02-17":76,"2021-03-20":98,"2021-04-12":100,"2021-05-04":87}},"Sally":{"tests":{"2021-02-01":87,"2021-02-17":94,"2021-03-20":98,"2021-04-12":78,"2021-05-04":84}},"Grace":{"tests":{"2021-02-01":97,"2021-02-17":88,"2021-03-20":98,"2021-04-12":82,"2021-05-04":83}}}

```
```
JSON Structure:
{
  "Tom": {
    "tests": {
      "2021-02-01": 89,
      "2021-02-17": 76,
      "2021-03-20": 98,
      "2021-04-12": 100,
      "2021-05-04": 87
    }
  },
  "Sally": {
    "tests": {
      "2021-02-01": 87,
      "2021-02-17": 94,
      "2021-03-20": 98,
      "2021-04-12": 78,
      "2021-05-04": 84
    }
  },
  "Grace": {
    "tests": {
      "2021-02-01": 97,
      "2021-02-17": 88,
      "2021-03-20": 98,
      "2021-04-12": 82,
      "2021-05-04": 83
    }
  }
}
```
