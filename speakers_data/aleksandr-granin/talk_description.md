Параллельное программирование - тема очень многогранная и глубокая. За десятки лет исследований было выработано огромное количество подходов, практик и инструментов, но вряд ли мы можем считать, что язык C++ успевал за этими тенденциями. Начиная со стандарта C++11, были введены такие концепции как std::thread, std::atomic, std::future, std::mutex, а в будущем ожидается, что будут добавлены coroutines - модель асинхронных вычислений. Что ж, это все интересные вещи для изучения, - но речь в докладе пойдет о совершенно ином подходе. Software Transactional Memory (STM) - концепция транзакционно изменяемой модели данных - существует уже давно и имеет ряд реализаций для всех языков. Однако неясными остаются три вопроса: какие есть сценарии использования этой концепции, в чем ее особенности, и что нам может предложить мир С++.
