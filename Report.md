# Отчёт о тестировании Money Transfer
## Краткое описание
26/03/2021 - 26/03/2021 было проведено функциональное тестирование приложения **Money Transfer**.    
 
На тестирование затрачено: 2 часа    
 
В результате тестирования выявлен дефект:    

* [Отрицательная итоговая сумма при сложении двух положительных целых чисел](https://github.com/Maksim-Shalaev/Money-Transfer/issues/1)  

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:  
 
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* Прописанный код
    
		public class Main { public static void main(String[] args) {
        int account = 2_000_000_000;
        int transfer = 500_000_000;
        int total = account + transfer;
        System.out.println("Total: " + total);}}

В качестве тестовых данных использовались данные:   

* Переменные для тестирования взяты из [условия задачи #1](https://github.com/netology-code/javaqa-homeworks/tree/master/programming) 
  
 * Текущий баланс счета- `account`
 * Сумма перевода- `transfer`
  
   
Тестирование производилось в следующем окружении: 

* Windows 7   
* Java 11.0.10  
* Intellij IDEA Community 2020.3