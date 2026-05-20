# Andrey Andrenkov

## Junior Frontend Developer

![My photo](https://via.placeholder.com/150?text=Hanna+Voloshyna)  
*Replace with your actual photo URL*

---

### Contact information

- **Phone:** +38 068 4489766  
- **Email:** awdawdawdawdaa@gmail.com  
- **Telegram:** [@awdawdawdadadaa](https://t.me/awdawdwadawddaw)  
- **LinkedIn:** [linkedin.com/in/awdawdawdawwadawdad](https://linkedin.com/in/awdadawdawdawd)  
- **Behance:** [behance.net/hawdawdawdawdwa](https://behance.net/awdawdawd)  
- **GitHub:** [github.com/awdawdawdawdawda](https://github.com/awdawdadawda)

---

### Briefly About Myself

Starting my career as a layout designer in a local newspaper with minimum skills, I became proficient in printing design.  
My keen interest in printing technologies led me to work as a Prepress and DTP Engineer in the largest printing house in my city, where I continued self-learning, examining the process of creating wine and food labels, magazines and other printed goods.

Three years ago I became passionate about retouching. I’ve mastered different retouching techniques, learned to work with a graphic tablet, become an advanced Photoshop user and found my first job as a retoucher.

Remote work as a retoucher gives me extra free time, which I spend learning Frontend Development.  
I’m interested in Web Development because this occupation provides endless possibilities for professional growth. Also, there are huge amounts of free high-quality resources for self-education and a large community of developers.

I believe my ability to learn and gain new skills will lead me through this path of becoming a proficient Frontend Developer.

---

### Skills and Proficiency

- HTML5, CSS3  
- JavaScript (Basics)  
- Git, GitHub  
- VS Code, IntelliJ IDEA  
- Adobe Photoshop, Illustrator, InDesign  

---

### Code Example

**Peak array index KATA from CODEWARS**  
*Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the leftmost index.*

```javascript
function peak(arr) {
  for (let i = 0; i < arr.length; i++) {
    let leftSum = arr.slice(0, i).reduce((a, b) => a + b, 0);
    let rightSum = arr.slice(i + 1).reduce((a, b) => a + b, 0);
    if (leftSum === rightSum) return i;
  }
  return -1;
}
