# philo

Решение задачи об обедающих философах.


Запуск основной части:

  make
  
  ./philosophers 2 410 200 200 5


// где первое число - количество философов, второе - время жизни одного философа, третья - время одного приема пищи, четвертая - время сна философа

// пятая цифра - это количество приемов пищи, для каждого из философов, после которого действие работы программы завершается

// пятая цифра не является обязательной, без указания пятой цифры программа будет работать бесконечно (или пока не умрет философ)
 
 
Запуск бонусной части:

  make bonus
  
  ./bonus_philosophers 2 410 200 200 5
  
  
Задача:

Пять безмолвных философов сидят вокруг круглого стола, перед каждым философом стоит тарелка спагетти. Вилки лежат на столе между каждой парой ближайших философов.
Каждый философ может либо есть, либо размышлять, либо спать. Приём пищи не ограничен количеством оставшихся спагетти — подразумевается бесконечный запас. Тем не менее, философ может есть только тогда, когда держит две вилки — взятую справа и слева. Как только филосов проснулся он начинает размышлять (ждать освобождения своих вилок), как только вилки доступны он берет вилки и начанает есть, закончив прием пищи он бросает вилки и засыпает.
Каждый философ может взять ближайшую вилку (если она доступна) или положить — если он уже держит её. Взятие каждой вилки и возвращение её на стол являются раздельными действиями, которые должны выполняться одно за другим.
Вопрос задачи заключается в том, чтобы разработать модель поведения (параллельный алгоритм), при котором ни один из философов не будет голодать, то есть будет вечно чередовать приём пищи и размышления.
