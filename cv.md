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
