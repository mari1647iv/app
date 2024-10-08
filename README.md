# Туториал по Git и GtHub

## README Репозитория
`README.md` - специальный файл в репозитории, содержащий описание и документацию всего проекта или его частей. Для форматирования README используется разметка Markdown.

### Заголовки 

Для обозначения заголовков используется последовательность решеток `#` и отступ перед самим текстом.

```Markdown
# Заголовок 1
## Заголовок 2
### Заголовок 3
#### Заголовок 4
##### Заголовок 5
###### Заголовок 6
```
# Заголовок 1
## Заголовок 2
### Заголовок 3
#### Заголовок 4
##### Заголовок 5
###### Заголовок 6

### Форматирование текста

```
Обычный текст  
_Курсив 1_  
*Курсив 2*  
**Жирный текст**  
***Жирный курсив***  
~~Зачеркнутый текст~~  
`Моноширинный текст`

<ins>Подчеркнутый текст 1</ins>
<u>Подчеркнутый текст 2</u>  
```

Обычный текст  
_Курсив 1_  
*Курсив 2*  
**Жирный текст**  
***Жирный курсив***  
~~Зачеркнутый текст~~  
`Моноширинный текст`

<ins>Подчеркнутый текст 1</ins>  
<u>Подчеркнутый текст 2</u>  

### Цитатирование

```
> Первая часть цитаты
>
> Вторая часть цитаты
```

> Первая часть цитаты
>
> Вторая часть цитаты

```
> Цитата
>
>> Вложенная цитата
```

> Цитата
>
>> Вложенная цитата

```
> ### Форматированный цитатный блок
>
> - Первый элемент.
> - Второй элемент.
>
>  *Блоки цитат* могут сочитаться с другими `элементами разметки`.
```

> ### Форматированный цитатный блок
>
> - Первый элемент.
> - Второй элемент.
>
>  *Блоки цитат* могут сочитаться с другими `элементами разметки`.

### Перенос строки и разделительные черты

```
 <br/>
 <hr/>
 ---
 ***
 ___
```
Это перенос строки с помощью `html`

 <br/>
 <br/>

Это разделительная черта с помощью `html`

<hr/>

Это разделительная черта с помощью `Markdown`

---

### Списки

#### Неупорядоченный список

```
- Первый элемент
- Второй элемент
  - Второй уровень
    - Третий уровень
      - и т.д.

* Первый элемент
* Второй элемент
  * Второй уровень
    * Третий уровень
      * и т.д.

+ Первый элемент
+ Второй элемент
  + Второй уровень
    + Третий уровень
      + и т.д.
```

- Первый <span style="color:red">элемент</span>
- Второй элемент
  - Второй уровень
    - Третий уровень
      - и т.д.
  


#### Упорядоченный список

```
1. Первый элемент
2. Второй элемент
   1. Второй уровень
      1. Третий уровень
         1. и т.д.

```
1. Первый элемент
2. Второй элемент
   1. Второй уровень
      1. Третий уровень
         1. и т.д.


### Ссылки

```
<https://www.markdownguide.org>  
[Google.com](https://www.google.com)
```

<https://www.markdownguide.org>  
[Ссылка на Google.com](https://www.google.com)

### Изображения

```
![Маскот Линукс](https://mdg.imgix.net/assets/images/tux.png)
```

![Маскот Линукс](https://mdg.imgix.net/assets/images/tux.png)

### Код

```
`элемент кода`

    ```
      блок кода
    ```
```

`элемент кода`

```
  блок кода
```

### Специальные символы

Чтобы отобразить специальные символы, Markdown использует `\`.

```
\*  
\/  
\\  
\-  
\+  
\`  
```

\*  
\/  
\\  
\-  
\+  
\`  

### HTML

Markdown поддерживает и может быть скомбинирован с языком разметки HTML.

```
<h2>Заголовок</h2>

<p>Текст <em>параграфа</em>.</p>

<a href="https://www.markdownguide.org">Официальная документация Markdown</a>
```

<h2>Заголовок</h2>

<p>Текст <em>параграфа</em>.</p>

<a href="https://www.markdownguide.org">Официальная документация Markdown</a>

<button onclick="this.style.color = 'green'">Button</button>

<form>
<input type="date"/>
</form>

<style>
  button {
    background-color: lightcyan;
    padding: 5px 15px;
    border: none;
    color: grey;
  }
</style>
