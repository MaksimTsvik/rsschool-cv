# MAKSIM TSVIK

**Personal details**

* 10 December 1987; Minsk, Belarus
* +375 29 626 93 57 (BY)
* +86 136 8093 3284 (CN)
* [mkdemix@tut.by](mailto:mkdemix@tut.by)
* [LinkedIn](www.linkedin.com/in/maksim-tsvik)
* [GitHub](https://github.com/MaksimTsvik)

## About me

I am a professional Mechanical Engineer and now decided to retrain as a front-end developer.
Reliable, responsible, easy-going and quick-learner these are main characteristic about me.
I know how to perform tasks well, able to prioritize quickly and make right decision after weghing up all pros and cons.

## Training

1. [HTML Academy](https://htmlacademy.ru/)
2. [Learn JS](https://learn.javascript.ru/)
3. [Codewars](https://www.codewars.com/)

## Skills

* HTML and CSS
* JavaScript
* Git
* Agile/Waterfall
* SQL
* Java (Core)

## `Code` example - Recursive *array depth* calculator

``` javascript
class DepthCalculator {

  calculateDepth(array) {
    // Add array counter
    let count = 1
    // Return 0 is it is not array
    if (!Array.isArray(array)) {
      return 0
    }
    // if it is array - calculate nested arrays count via reducer and recursion
    let nestedCount = array.reduce((count, next) => {
      if (Array.isArray(next)) {
        let newCount = this.calculateDepth(next);
        return count > newCount ? count : newCount;
      }
      return count;
    }, 0)
    // Return total count
    return count + nestedCount
  }
};
```

## Languages

1. Russian\Belarusian - `native`
2. English - `B2+`
3. Mandarin - `A1`
4. German - `A1`
## Overall

### Education

* 9.2009 - 1.2011  **Bachelor degree as Interpreter (English)**\
    *State educational institution "Academy of Postgraduate Education"*
* 7.2005 - 6.2010 **Bachelor degree as Engineer, management specialist**\
    *Belarusian National Technical University*

### Professional experience

* Since 9.2019 **Mechanical engineer, LAB engineer (R&D and Prototyping)**\
    *[EPAM Systems Inc.](https://www.epam.com/), ESID MRL*
* 6.2017 - 9.2019 **Warranty and service engineer in SEA region**\
    *[Izovac Ltd.](https://www.izovac.com/)*
* 6.2015 - 6.2017 **Regional representative in the Republic of Belarus**\
    *[LLC 'Izmerenie i control'](https://izmerkon.ru/)*
* 7.2010 - 6.2015 **Chief of Staff (military rank - Captain)**\
    *[Military unit 31802](https://www.mil.by)*

### Voluntary experience

* 2011-2014 Head of mine cleaning ation team.
* Since 2011 – Bioreactor for decellularization (PoC/Alpha).
* 2020 – COVID-19 volunteer: 
    * protective cover;
    * UV sterilization box;
    * bactericidal UV recirculator.

### Other

* System thinking.
* High speed of work.
* Responsibility for achieving results.
* Stress resistance.
* Ability to organize people for the tasks.