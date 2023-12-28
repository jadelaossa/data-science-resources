---
creation date: 2023-12-28 21:35
modification date: 2023-12-28 21:35
link: https://medium.com/towards-data-science/how-to-create-fake-data-with-faker-a835e5b7a9d9
author: Khuyen Tran
---

<< _Creation date_: [[2023-12-27]] | _Modification date_: [[2023-12-29]] >>


## <u>TL;DR</u>

Python package that allows to create fake data in one line of code.
https://github.com/joke2k/faker/tree/master


## <u>Key Takeaways</u>

- Really useful library to create fake data quickly and in only one line of code.
- Multitude of methods to create different types of data.

## <u>Code snippets</u>

```Python
# pip install Faker
from faker import Faker


fake = Faker()

# Some basic methods
>>> fake.color_name()
'Sea Green'

>>> fake.name()  
'Vanessa Schroeder'

>>> fake.address()  
'3138 Jennings Shore\nPort Anthony, MT 90833'

>>> fake.job()  
'Buyer, industrial'

>>> fake.date_of_birth(minimum_age=30)  
datetime.date(1906, 9, 18)

>>> fake.city()  
'Rebeccastad'

# It's possible to crate entire fake profiles
fake.profile()

```

## <u>Other notes and questions</u>
 



- <u>Tags</u>: #DataScienceTools
- <u>Related</u>:

> [!quote] The function of wisdom is to discriminate between good and evil.
> — Cicero