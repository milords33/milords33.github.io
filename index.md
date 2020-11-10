<html lang="en">

<!--  task 1  -->

<head>
    <meta charset="UTF-8">
    <meta name="description" CONTENT="Formula h2o">
    <title>ControlWork</title>

    <link rel="stylesheet" type="text/css" href="styleC.css" />
</head>

<body>
    <!--   task 2   -->
    <div>
        <h1> Книжная <span class="siteName">лавка</span> </h1>
        <h2> Здесь вы сможете найти журналы, книги, статьи</h2>
        <h3> а возможно и новых друзей :) </h3>
    </div>

    <!--  task 3  -->
    <div>
        <h3>Наши главные особенности:</h3>
        <p class="task3"> Хорошая поддержка </p>
        <p class="task3"> Быстрая доставка </p>
        <p class="task3"> Чат, в котором вы сможете найти друзей </p>
    </div>

    <!--  task 4  -->
    <div>
        <img src="bookPhoto1.jpeg" width="200" height="200" alt="Книги">
        <img src="necklace.jpg" width="200" height="200" alt="Ожерелье">
        <img src="view.jpg" width="200" height="200" alt="Вид">
    </div>

    <!--  task 5  -->
    <div>
        <h3> Самые активные пользователи </h3>

        <!--  Нумерованный список  -->
        <div>
            <ol>
                <li> Danya3311</li>
                <li> WhatIsLove</li>
                <li> Ragnarek</li>
            </ol>
        </div>
        <h3> Наши партнеры</h3>

        <!--  не нумерованный список  -->
        <div>
            <ul>
                <li> Google </li>
                <li> facebook</li>
                <li> youtube</li>
            </ul>
        </div>

    </div>

    <!--  task 6  -->
    <div>
        <h3> Регистры</h3>
        <!-- Нижний регистр H2O -->
        <div>
            <span> H<sub>2</sub>O </span>
        </div>

        <!--  Верхний регистр x2-->
        <div>
            <span> x<sup>2</sup> </span>
        </div>
    </div>

    <!--  task 7  -->
    <div>
        <h3> Форма </h3>
        <form method="post">

            <!-- Инпуты -->
            <div>
                <label for="username">Имя пользователя</label><br>
                <input name="username" type="text"><br>

                <label for="numb">Ваш номер в списке</label><br>
                <input type="number" name="numb"><br>


            </div>

            <!--   Чекбокс   -->
            <div>
                <p>
                    <label for="rulesAgreement">Вы согласны с правилами использования?</label>
                    <input type="checkbox" name="rulesAgreement" id="rulesAgreement"><br>

                    <label for="rulesAgreement">Вы согласны на нашу расслыку?</label>
                    <input type="checkbox" name="Newsletter" id="Newsletter"><br>
                </p>
            </div>

            <!-- Радиобаттон -->
            <div>
                <span> Ваш пол:</span>
                <p>

                    <input type="radio" name="gender" id="male" value="Male">
                    <label for="male">Мужчина</label><br>

                    <input type="radio" name="gender" id="female" value="Female">
                    <label for="female">Женщина</label><br>
                </p>
            </div>

            <!-- Мультиселект -->
            <div>
                <span>Ваша любимая стихия</span>
                <p>

                    <select multiple>
                        <option>Огонь</option>
                        <option>Вода</option>
                        <option>Земля</option>
                        <option>Воздух</option>
                    </select></p>

            </div>

            <!--  text area  -->
            <div>
                <label for="description">Расскажите, чего вы ждёте от нашего знакомства</label><br>
                <textarea name="description" id="description"></textarea><br>
            </div>

            <!-- Отправка формы -->
            <div>
                <button type="submit">Отправить</button>
            </div>
        </form>
    </div>
</body>

</html>
