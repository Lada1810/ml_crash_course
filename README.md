Работу выполнили студенты группы М8О-214М-21  
Русина Лада
Вихирев Алексей
Меньков Андрей

В работе использована RNN нейросейть на основе LSTM (tensorflow keras)  


В результате подбора параметров удалось достичь точности в 0.88. 
Был произведен анализ датасета, в ходе которого было установлено, что количество уникальных слов в тестах 14000+, средняя длина предложений 35 слов.
Поэтому в качестве параметров был выбран размер словаря 14000 и размер embeddingа в 32.

Перед использованием, полученные тексты очищались от спецсимволов и цифр, приводились к нижнему регистру, убирались стоп слова. 

Посмотреть, как производился анализ датасета можно в файле
