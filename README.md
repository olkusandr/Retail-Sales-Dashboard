![image](https://github.com/user-attachments/assets/4f6ff947-31d6-44ca-9467-ccee78fec7f1)
# Заголовок 1
## Заголовок 2
### Заголовок 3
## 📊 Функціонал дашборду

1.  Перший пункт
2. Другий пункт

**Кількість товарів в чеку визначалася за рахунок додавання такої міри:**

```dax
Кількіddарів в чеку = AVERAGEX(
    SUMMARIZE(
        'рПродажіФакт',
        'рПродажddfека], 
        "Н", sumdgажіФакт'[К-ть])
    ),
    [Н]
)
```

Продовження звичайного тексту
