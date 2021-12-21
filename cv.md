# Kruchkova Darya Sergeevna


## Date of birth: 10.06.1992

## My contact
1. Country: Belarus
2. Town: Gomel
3. E-mail: t.darjas@rambler.ru
4. Discord: Darya Kruchkova (@daryakruchkova)

## About myself
I graduated from the Belorussian State University of Transport in 2014. I work as a design engineer. Extremely motivated for career change goal. Now I am studying a new profession. I want to be a Front-End developer.

## Professional skils
1. HTML, CSS - elementary level
2. Languages - English (a1)

## Code example
const buttonCheck = document.querySelector('.check');
 
buttonCheck.addEventListener('click', () => {
    let number = tel.value.split('');
    let flag = true;

    let firstNumbers = number.slice(0, 4).join('');
    let onlyNumbers = number.slice(4, number.length);

    if(firstNumbers !== "+375" || number.length !== 13) flag = false;

    for (let num of onlyNumbers){
        num = Number(num);
        if(Number.isNaN(num)) flag = false;
    }

    if(!flag) {
        alert("Неверный формат номера телефона!");
    }
})

## Education
Belorussian State University of Transport, Civil Engineering Faculty


