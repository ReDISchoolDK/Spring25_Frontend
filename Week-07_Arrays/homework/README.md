# Homework Week 7

Submit your exercise by creating a Pull Request.

# Who reviews your home work? 🧛‍♀️

- You have to generate the home work submission list
- Randomly assign students to teachers
- You have students and teachers array below
- save the result in a array of objects `[ {...}, {...}, {...} ]`
- print the result in console.log()
- once your code works then manually include one more student in the array list, (just type a new student name in the array list)
- then, run the program, it should still assign properly
- then try to include one more teacher; still, the program should work. 🙂

# Tips

- shuffle students array
- shuffle teachers array
- pick first student, pick first teacher and assign them.

## Tip - How to shuffle an array

```javascript
const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];
const shuffled = numbers.sort(() => Math.random() - 0.5);
console.log(shuffled);
```

## Tip - Create object with map

```javascript
const numbers = [1, 2, 3, 4];
const obj = numbers.map((n) => ({ property: n }));
console.log(obj);

//Output
//
// [
//   {
//     "property": 1
//   },
//   {
//     "property": 2
//   },
//   {
//     "property": 3
//   },
//   {
//     "property": 4
//   }
// ]
```

# Use below code as a starting point

```javascript
const students = ["s1", "s2", "s3"];
const teachers = ["t1", "t2"];

//*** your code here ***

//expected output
//
// [
//   {student: "s1", teacher : "t2"},
//   {student: "s2", teacher : "t2"},
//   {student: "s3", teacher : "t1"},
// ]
```

# You can use below sample array

```javascript
const students = [
  "Mehrnoosh",
  "Maria",
  "Oumaima",
  "Yiting",
  "Sunitha",
  "Sukhwinder",
  "Prachi",
  "Busra",
  "Paloma",
  "Annamani",
  "Sravani",
  "Natalia",
  "Fatima",
  "Tejaswini",
  "Fulya",
  "Gloryfel",
];

const teachers = ["Henderson", "Tifana", "Iga", "Engiber", "Kumaran", "Lukáš", "Tim"];
```

To submit, create a new repository in your own account by Sunday 18:00 and send the link to your assigned teacher via Slack. We will send out the assignments.
