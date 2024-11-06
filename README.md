<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Задание 4</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
  <div class="header">
    <header>
      <img src="logo.png" id="img" alt="Описание картинки для скрин-ридеров и поисковиков" />
      <h1 id="name">Название сайта</h1>      
  </header>
    <nav>
      <nav class="navbar navbar-expand-lg  bg-body-tertiary">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Меню сайта -></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Домой</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Ссылки</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Меню
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Пункт меню 1</a></li>
                  <li><a class="dropdown-item" href="#">Пункт меню 2</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Пункт меню 3</a></li>
                </ul>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Поиск</button>
            </form>
          </div>
        </div>
      </nav>
  </div>
    
    <main>
      <div class="d-block d-lg-none mt-4 p-4" >
        <table class="table table-striped">
          <thead>
            <tr>
              <th scope="col">#</th>
              <th scope="col">Первая</th>
              <th scope="col">Вторая</th>
              <th scope="col">Третья</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row">1</th>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <th scope="row">2</th>
              <td></td>
              <td></td>
              <td></td>
            </tr>
            <tr>
              <th scope="row">3</th>
              <td></td>
              <td></td>
              <td></td>
            </tr>
          </tbody>
        </table>
        <br /> 
      </div>

      
      <h2>Список гиперссылок</h2>
        <div class="links">
          <br/>
          <ul>
            <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
            <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
	    <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
            <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
            <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
	    <li><a href="http://kubsu.ru">kubsu.ru (HTTP)</a></li><br />
        </ul>
        </div>
        <div class="d-none d-lg-block mb-3 order-lg-1" >
          <table class="table table-striped">
            <thead>
              <tr>
                <th scope="col">#</th>
                <th scope="col">Первая</th>
                <th scope="col">Вторая</th>
                <th scope="col">Третья</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <th scope="row">1</th>
                <td></td>
                <td></td>
                <td></td>
              </tr>
              <tr>
                <th scope="row">2</th>
                <td></td>
                <td></td>
                <td></td>
              </tr>
              <tr>
                <th scope="row">3</th>
                <td></td>
                <td></td>
                <td></td>
              </tr>
            </tbody>
          </table>
          <br /> 
        </div>
      <div class="form">
        <h2>Форма</h2>
        <form>
          <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">ФИО</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <div id="emailHelp" class="form-text">Ведите ФИО</div>
          </div>
          <div class="mb-3">
            <label for="exampleInputEmail1" class="form-label">Email</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
            <div id="emailHelp" class="form-text">Введите свой Email</div>
          </div>
          <label>
            Дата рождения:<br />
            <input 
              name="birthdate" 
              type="date"
            />
          </label>
          <br>
          Пол
          <br>
          <div class="form-check">
            <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
            <label class="form-check-label" for="flexRadioDefault1">
              Мужской
            </label>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" checked>
            <label class="form-check-label" for="flexRadioDefault2">
              Женский
            </label>
          </div>
          <br>
          <select class="form-select" aria-label="Default select example">
            <option value="pascal" selected="selected">Pascal</option>
              <option value="c" selected="selected">C</option>
              <option value="cpp" selected="selected">C++</option>
              <option value="javascript" selected="selected">JavaScript</option>
              <option value="php" selected="selected">PHP</option>
              <option value="python" selected="selected">Python</option>
              <option value="java" selected="selected">Java</option>
              <option value="haskell" selected="selected">Haskell</option>
              <option value="clojure" selected="selected">Clojure</option>
              <option value="prolog" selected="selected">Prolog</option>
              <option value="scala" selected="selected">Scala</option>
              <option value="Lang" selected="selected">Ваш любимый язык программирования</option>
          </select>
          <div class="form-floating">
            <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
            <label for="floatingTextarea2">Биография</label>
          </div>
          <div class="mb-3 form-check">
            <input type="checkbox" class="form-check-input" id="exampleCheck1">
            <label class="form-check-label" for="exampleCheck1">Всё верно</label>
          </div>
          <button type="submit" class="btn btn-primary">Отправить</button>
        </form>
      </div>
    </main>
    <footer>
        <p>FOOTER</p>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html>
