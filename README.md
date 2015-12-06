# Description

This repository has contents for the application 'Edua Story'.
There are two kind of files.

## lessons.json

This file is a table contents of lessons. The structure of it is here.

* It starts with "[" and ends with "]"
* It has some lessons that starts with "{" and ends with "},"
* Each lesson has "no" field and "title" field.
* The "no" field allowed numeric only. (OK: 10 / NG: a, 10b, 1.2, etc.)

This is a sample of lessons.json file.

```json
[
  {"no": "1", "title": "You visit Japan"},
  {"no": "2", "title": "Do you like sushi?"},
  {"no": "3", "title": "Facebook is fun!"},
]
```

## <i>no</i>.zip

This file is a zip archive includes contents of a lesson. <i>no</i> have to be replaced by a value of "no" field defined in lessons.json file (ex. 1.zip). Every file is required. Every jpg file's size is 480x720. The structure of it is here.

| filename | description |
| ------------- | ------- |
| answer1_1.txt | The candidate of answer for question1. This is a correct answer. |
| answer1_2.txt | The candidate of answer for question1. This is a wrong answer. |
| answer2_1.txt | The candidate of answer for question2. This is a correct answer. |
| answer2_2.txt | The candidate of answer for question2. This is a wrong answer. |
| first_narration.txt | The first narration text |
| last_message.jpg | An image for the last narration |
| last_message.txt | The last narration text |
| narration1.jpg | An image for narration1.txt |
| narration1.txt | The narration text for neither question1 nor question2 is corrent. |
| narration2.jpg | An image for narration2.txt |
| narration2.txt | The narration text for only question1 is corrent. |
| narration3.jpg | An image for narration3.txt |
| narration3.txt | The narration text for only question2 is corrent. |
| narration4.jpg | An image for narration4.txt |
| narration4.txt | The narration text for either question1 and question2 is corrent. |
| question1.jpg | An image for question1.txt |
| question1.txt | The text of a first question. |
| question2.jpg | An image for question2.txt |
| question2.txt | The text of a second question. |
| reaction1_1.jpg | An image for reaction1_1.txt |
| reaction1_1.txt | The text choicing a correct answer of question1. |
| reaction1_2.jpg | An image for reaction1_2.txt |
| reaction1_2.txt | The text choicing a wrong answer of question1. |
| reaction2_1.jpg | An image for reaction2_1.txt |
| reaction2_1.txt | The text choicing a correct answer of question2. |
| reaction2_2.jpg | An image for reaction2_2.txt |
| reaction2_2.txt | The text choicing a wrong answer of question2. |
| title.txt | The title text of this lesson. |
