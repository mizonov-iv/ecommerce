<template>
  <nav class="container nav">
    <div class="nav__logo"></div>
    <ul class="nav__list">
      <li class="nav__item">Все товары</li>
      <li class="nav__item">
        <a class="nav__link" href="#">Одежда</a>
        <ul class="nav__list--dropdown">
          <li class="dropdown-list__item">Вся одежда</li>
          <li class="dropdown-list__item">Худи и свитшоты</li>
          <li class="dropdown-list__item">Футболки</li>
          <li class="dropdown-list__item">Штаны</li>
          <li class="dropdown-list__item">Шорты</li>
          <li class="dropdown-list__item">Костюмы</li>
          <li class="dropdown-list__item">Жилетки</li>
          <li class="dropdown-list__item">Облегченная коллекция</li>
          <li class="dropdown-list__item">Утепленная коллекция</li>
        </ul>
      </li>
      <li class="nav__item">
        <a class="nav__link" href="">Аксессуары</a>
        <ul class="nav__list--dropdown">
          <li class="dropdown-list__item">Все аксессуары</li>
          <li class="dropdown-list__item">Рюкзак Born To Be 3.2</li>
          <li class="dropdown-list__item">Сумки</li>
          <li class="dropdown-list__item">Носки</li>
          <li class="dropdown-list__item">Нижнее белье</li>
          <li class="dropdown-list__item">Кепки</li>
          <li class="dropdown-list__item">Украшения</li>
        </ul>
      </li>
      <li class="nav__item">Скидки</li>
      <li class="nav__item">Подарочные сертификаты</li>
    </ul>
    <div class="nav__about">
      <div class="nav__about-wrap">
        <div class="nav__pin"></div>
        <p>Магазины</p>
      </div>
      <p class="nav__about-brand">О бренде</p>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>