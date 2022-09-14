# Mikalai Hancharonak

### Contact information

Phone: +375 29 249 03 31  
E-mail: Classic76@tut.by  
Telegram: @N1kFreeman  
Discord: NikFreeman

### Briefly about yourself

Graduated from Vitebsk State University with a degree in Mathematics and Computer Science.

He worked as a school teacher.

After that, he moved to work in the editorial office of the regional newspaper "Patryet", engaged in newspaper layout, photo retouching. _(Adobe Photoshop, InDesign, Corel Draw)_.

Then he continued his career in the automation department of Belarusbank OJSC. _(Novell administration, user support, automation of routine actions)_.

After the reorganization of the branch of Belarusbank OJSC, he was engaged in freelancing. Developed and implemented a project to automate the work of the central district hospital. (Patient card management, creation of doctors' work schedules, electronic queue, medical examination, reporting system, patient admission) _(Delphi, MSSQL Server, VBA for Application, Cristal Report)_.

Then he worked as the head of the Information Technology Department of JSC Belagroprombank. _(Novell administration, Active Directory, user support, antivirus protection, installation of software updates)_.

After the reorganization of the Information Technology department, I moved to the position of head of the Retail sales Department of JSC Belagroprombank _(I am engaged in advertising, sales funnels, processing arrays of information for the formation of commercial lists, concluding contracts)_.

The purpose of studying at RSSchool is to acquire new skills in development, to increase opportunities in the labor market.

### Skills and Proficiency

HTML5, CSS3  
SQL  
VBA for Aplication  
Git, GitHub  
VS Code, MS VS Community
Adobe Photoshop, Corel Draw, InDesign

### Code example

ROT13 is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet. ROT13 is an example of the Caesar cipher.

Create a function that takes a string and returns the string ciphered with Rot13. If there are numbers or special characters included in the string, they should be returned as they are. Only letters from the latin/english alphabet should be shifted, like in the original Rot13 "implementation".

```
function rot13(message){
  //your code here
    let Shablon ='ABCDEFGHIJKLMNOPQRSTUVWXYZ';
    let res ='';
    for (let chr of message)
      {
        let x=chr.toUpperCase();
        if (Shablon.indexOf(x) === -1) {res +=chr}
          else
          {
           let i=(Shablon.indexOf(x)+13) % 26;
           if (x === chr) {res +=Shablon[i]}
             else
             {
              res +=Shablon[i].toLowerCase();
             }
          }
      }
    return res;
}
```

### Education

- higher (Vitebsk State University).
- SQL (<https://sql-ex.ru>)
- HTML and CSS (<https://codecademy.com> and <https://metanit.com>)
- JavaScript <https://learn.javascript.ru/>

### Language

English level - A2
