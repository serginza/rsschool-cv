##### PERSONAL INFORMATION

***Name:** Sergey Polikarpov*

***Date if birth:** 10 july 1996*

***E-mail:** polikarpov-sereg@mail.ru*

***Tel.:** +7(999)138-O2-27*

##### EDUCATION AND TRAINING

*September 2014 - june 2018*
Nizhny Novgorod State Technical University
BA in Automation of Technical Processes & Productions;

*September 2018 - june 2020*
Nizhny Novgorod State Technical University
MA (Hons) in Automation of Technical Processes & Productions;

*November 2018 - june 2019*
LET-NN, English course A2.

##### SKILLS

Basic syntax of JavaScript, HTML, CSS, page-proofs on layout.

##### EXPERIENCE

***ToDo List** with saving data via LocalStorage and local server (REST API, node js);

***Calendar app** with weather API.

##### ABOUT ME

Responsibly and conscientiously I treat the assigned tasks, I am ready to learn new methods of performing tasks, I am friendly and polite in communication with colleagues, I strive to do my job efficiently, I am aimed at professional development and career growth, I can work in a team, I try to solve tasks creatively and analytically.

##### CODE EXAMLE

*function Weather API for calendar app:*

async function weather() {
    
    fetch("http://api.openweathermap.org/data/2.5/weather?id=250555..")
        .then(res => res.json())
            .then(data => {
                console.log(data);

                let textTemp = document.querySelector(".weather-temp");
                let temp = Math.round((data.main.temp -273));

                (temp > 0) ? textTemp.textContent = "+" + temp + "°" :
                (temp < 0) ? textTemp.textContent = "-" + temp + "°" :
                textTemp.textContent = temp + "°";
            });
}

##### LANGUAGES

Native Russian;

English B1, communicated with native speakers abroad.