# **Nastassia Bialova**

![Profile](/avatar.jpg)

*email:* nastjabelova0@gmail.com

*linkedin:* nastya-fianit

*discord:* Nastya(@nastya-student)

## **About:** 

*I continue learning computer science and programming, including frontend development.
I have extensive work experience in the railway and postal service. Now I am interested in IT and tend to seek a career change in the future. Looking for some ideas for pet-projects.*

## **Skills** [basics]: 

Java (primary language), test automation, Git, Jenkins, Maven, Selenium, Rest Assured, Intellij, PyCharm, Linux, Docker, computer network; familliar with HTML, CSS, JS, Python. 

## **Last solution:**

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
* 2023 - EPAM lab intership;
* 2024 - postal service.

## **Education:** 

* Belarussian State University of Transport;
* external training at EPAM "Automated testing with Java".
* Leverage MJC School and other platforms for self-education.

## **English:** 

B1. Had practical experience while communicating with an international team in the laboratory.