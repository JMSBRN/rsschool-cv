![img_1.jpg](https://github.com/JMSBRN/rsschool-cv/blob/gh-pages/images/img_1.jpg)
# Zakhavai Aliaksandr

# Contact me

E-Mail : zakhavai@gmail.com  
Phone : +375336389669  
Linkedin :https://Linkedin.com/in/zakhavai-aliaksandr-009bab73

Country/City : Belarus, Minsk.  

# Objective: JavaScript developer, 



 # Experience :   

* ## 2017-2021  
    * LLC Golden-Hill, Owner.  
* ## 2016-2017  
    * LLC Orion-Group, Owner with partner. 

* ## 2014-2016
    * FOC Kamako, Director of Sales Main Department.

# Education :

* ## 2018-2108  
  * Training Tachnologies Center, Java Standart Edition.
* ## 2013-2015  
  *  Akademia Laoona Kazminskiego(Kozminski University-Warsaw, Poland).  
  Executive MBA, International Economic Relations Commerce.  
* ## 2012-2013  
  * Foreign Language School https://mlight.by. 
  Enflish Pre-intermediat level.


# About Me-  
 *  Developing small projects, and learning new technologies.Versed in programming languages including HTML5, JavaScript, React, Java, MySQL  
 # Skills  

 * Project mengment, Complex propblem solver,  
 Creative, Innoative, Service-focused.   

 # Languages-
 * English-Pre-Intermediate.Polish-Speak and understand. ~~Romanian~~

 > 

 ## Single & Redy for __Relocation__     
   



  
_HTML_

``` 
<div id="MyClockDisplay" class="clock" onload="showTime()"></div> 
 ```
 ***CSS***
``` body {
    background: black;
}

.clock {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translateX(-50%) translateY(-50%);
    color: #17D4FE;
    font-size: 60px;
    font-family: Orbitron;
    letter-spacing: 7px;
   


}

```
**JavaScript**
```JavaScript
function showTime(){
    var date = new Date();
    var h = date.getHours(); // 0 - 23
    var m = date.getMinutes(); // 0 - 59
    var s = date.getSeconds(); // 0 - 59
    var session = "AM";
    
    if(h == 0){
        h = 12;
    }
    
    if(h > 12){
        h = h - 12;
        session = "PM";
    }
    
    h = (h < 10) ? "0" + h : h;
    m = (m < 10) ? "0" + m : m;
    s = (s < 10) ? "0" + s : s;
    
    var time = h + ":" + m + ":" + s + " " + session;
    document.getElementById("MyClockDisplay").innerText = time;
    document.getElementById("MyClockDisplay").textContent = time;
    
    setTimeout(showTime, 1000);
    
}

showTime();   
 ```



* # <i style="font-size: 25px" class="a1">It's just a watch! ) Who knows, maybe they can show the time more slowly...</i>
