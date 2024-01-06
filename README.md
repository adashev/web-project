### Оглавление <a name='toc'></a>
<ol>
<li><a href='#word_reference'>Вставить ссылку на слово</a></li>
<li><a href='#footnote'>Сноски</a></li>
<li><a href='#list_of_contents'>Автосодержание</a></li>
</ol>

# Вставить ссылку на слово <a name='word_reference'></a>

[ссылка на Ютубчик](https://www.youtube.com/)
текст текст
текст текст
текст текст
текст текст
текст текст
текст текст
текст текст
текст текст
текст текст
текст текст

# Сноски (VS CODE не отрисовывает) <a name='footnote'></a>

Если хотите делать сноски в тексте, то нужно сделать так: 

Here is a simple footnote [^1].

A footnote can also have multiple lines [^2].


[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

  # Автосодержание <a name='list_of_contents'></a>
если мы хотим создать авто оглавление, то около каждого заголовка нужно добавить специальный тег:
<a name='quote'></a>  В поле name можно писать все, что угодно, но лучше писать слово похожее на название заголовка. То есть полностью строка с заголовком будет выглядеть так: # Цитаты <a name='quote'></a>   И так нужно проделать с каждым заголовком, чтобы потом сформировать авто содержание. 
