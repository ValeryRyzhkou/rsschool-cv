# Valery Ryzhkou
---

## _Junior Frontend Developer_
---

### Contact information:

- Phone: +7 967 195 7172
- E-mail: valer4ik-larik@mail.ru
- Telegram: @lary_wildman
- [GitHub](https://github.com/ValeryRyzhkou)

---

### About me

I graduated from VSMU in 2016, worked as a doctor until January 2022, after which I moved to Moscow, where I decided for myself that it was time to become a programmer. Enrolled in courses at the developers bootcamp. Now I am improving my acquired knowledge and I want to work in Epam and relocate to another country.

---

### Skills

- HTML
- CSS
- Git, GitHub
- JavaScript(basic)
- Node.Js(basic)
- React(basic)

---

### Code example

```
const students = [
  { id: 2, name: 'Yevgeny', age: 18, groupId: 1 },
  { id: 7, name: 'Stepan', age: 18, groupId: 2 },
  { id: 1, name: 'Vasya', age: 19, groupId: 3 },
  { id: 1, name: 'Vova', age: 17, groupId: 3 },
  { id: 4, name: 'Natalia', age: 19, groupId: 1 },
  { id: 5, name: 'Andrei', age: 19, groupId: 2 },
  { id: 6, name: 'Kirill', age: 20, groupId: 1 }
  ];
  
  function myFunction(students) {
    const groups = [];
    const resultObj = {};
    const listOver17 = students.filter(el => el.age > 17);
    listOver17.forEach((el) => {
      if (!groups.includes(el.groupId)) {
        groups.push(el.groupId);
      }
    });
    groups.map(el => resultObj[el] = listOver17.filter(elem => elem.groupId === el));
    return resultObj
}
```
---

### Education

- __University__: Vitebsk state order of Friendship medical university, doctor
- __Courses__:
    - [Bootcamp of programmers Elbrus](https://elbrusboot.camp/#top)

---

### Languages

- English - A2(Elementary)
- Russian - Native
- Belorussian - Intermediate


