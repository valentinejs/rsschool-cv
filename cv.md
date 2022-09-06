#Valentine Borodich
---
##Contacts

Location: Minsk, Belarus
Email: valentine.borodich@mail.ru
GitHub: valentinejs
Number: +375 (44) 77-217-35
Discord: Valentin Borodich(@valentinejs)

---

##About me
I'm realy interested in become a programmer. I have never seen so cool and alive community in other industry. I sure I can become a part of it.

---
##Soft Skills

* a bit JS
* a bit Python
* a bit C++

---
##Code Example
The last task I finished:
```
You are given an array(list) strarr of strings and an integer k. 
Your task is to return the first longest string consisting of k consecutive strings taken in the array.

function longestConsec(strarr, k) {
  if (k <= 0 || strarr === [] || k > strarr.length) return '';
  let ans = '';
  for (let i = 0; i < strarr.length; i++) {
    let text = '';
    for (let j = i; j < i + k; j++) {
      if (typeof strarr[j] != 'undefined') text += strarr[j];
    }
    if (text.length > ans.length) ans = text;
  }
  return ans;
}
```
---
###Experience
All ahead =)

---
###Education
* __University__: Belarusian National Technical University
* __Specialization__: Electrical Engineer

---
###English level
A2 (I can read technical and non-technical texts, but can't speak freely)