# **Nastassia Bialova**

![Profile](/assets/img/avatar.jpg)

*email:* nastjabelova0@gmail.com

*linkedin:* [nastya-fianit](https://www.linkedin.com/in/nastya-fianit)

*discord:* Nastya(@nastya-student)

## **About:** 

*Self-educated IT-enthusiastic. Aimed to acuire programming experience.*

## **Skills** [basics]: 

Java (primary language), API and UI test automation, Git, Jenkins, Maven, Selenium Webdriver, TestNG, Rest Assured, Cucumber, Intellij, Linux, Docker, SQL, computer networks; familliar with HTML, CSS, JS, Python, Spring framework. 

## **Code example:**

[codewars task](https://www.codewars.com/kata/5270d0d18625160ada0000e4)

```
public class Greed{
  public static int greedy(int[] dice){
    int result = 0;
    for(int i = 0; i < dice.length; i++){
      if(dice[i] == 0){
        continue;
      }
      int count = 1;
      for(int j = i + 1; j < dice.length; j++){
        if(dice[i] == dice[j]){
          count ++;
          dice[j] = 0;
        }
      }
      result += countPoints(dice[i], count);
    }
    return result;
  }
  private static int countPoints(int number, int count){
    int points = (count / 3) * 100 * number;
    if(number == 1){
      points = points * 10 + (count % 3) * 100;
      }
    if(number == 5){
      points += (count % 3) * 50;
    }
      return points;
  }
}
```

## **Experience:** 

* 2010 - 2021 - Belarussian railway, ensuring train traffic safety;
* 2023 - EPAM lab intership (test automation with Java);
* 2024 - postal service.

## **Education:** 

* Belarussian State University of Transport;
* external training at EPAM "Automated testing with Java".
* Started learning in MJC School and RS School, leverage other platforms for education.

## **English:** 

B1. Had practical experience while communicating with an international team in the lab and some speaking clubs.