<template>
    <div class="home">
        <div class="header">
            <nav class="navbar navbar-expand-lg bg-body-tertiary">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#">EduTech</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                        aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarSupportedContent">
                        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                            <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#">Каталог</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Моё обучение</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Преподавание</a>
                            </li>
                        </ul>
                        <form class="d-flex" role="search">
                            <input class="form-control me-2" type="search" placeholder="Найти курс" aria-label="Search">
                            <button class="btn btn-outline-success" type="submit">Поиск</button>
                            <button class="btn btn btn-dark" style="margin-left: 10px;" type="submit">Войти</button>
                        </form>
                    </div>
                </div>
            </nav>
        </div>

        <div class="main">
            <div class="text-center">
                <img src="../image/homeLogo.png" class="img-home-logo">

                <h1 class="text-logo">Одна учетная запись для всего, что связано с EduTech.</h1>
                <div class="text-description">Войдите в систему, чтобы управлять аккаунтом.</div>

                <button type="button" class="btn btn-success mt-3 btn-lg">Войти</button>
                <div class="cards">


                    <div class="card" style="width: 21rem; background-color:#F5F5F5; border-radius: 20px; border: 0;">
                        <img src="../image/im1.png" style="width: 12%;">
                        <h4 style="margin-top: 10px;">Вы контролируете</h4>
                        <p class="card-text" style="text-align: left; font-size: 18px;">Просмотрите или обновите важную
                            информацию, такую как ваше имя, пароль и сведения о безопасности. Узнайте устройства,
                            подключенные к вашей учетной записи.</p>
                    </div>

                    <div class="card" style="width: 21rem; background-color:#F5F5F5; border-radius: 20px; border: 0;">
                        <img src="../image/im2.png" style="width: 15%;">
                        <h4 style="margin-top: 10px;">Безопасность</h4>
                        <p class="card-text" style="text-align: left; font-size: 18px;">Благодаря таким функциям
                            безопасности учетной записи, как двухфакторная аутентификация, EduTech помогает обеспечить
                            безопасность вашей учетной записи.</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="footer" style="margin-top: 100px;">
            <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top">
                <div class="col-md-4 d-flex align-items-center">
                    <a href="/" class="mb-3 me-2 mb-md-0 text-body-secondary text-decoration-none lh-1">
                        <svg class="bi" width="30" height="24">
                            <use xlink:href="#bootstrap"></use>
                        </svg>
                    </a>
                    <span class="mb-3 mb-md-0 text-body-secondary">© 2023 EduTech Company, Inc</span>
                </div>

                
            </footer>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
.img-home-logo {
    width: 23%;
    margin-top: 60px;
}

.text-logo {
    font-size: 28px;
    margin-top: 30px;
}

.cards {
    display: flex;
    justify-content: space-evenly;
    margin-top: 50px;
}

.card {
    padding: 20px;
    display: flex;
    align-items: flex-start;
}</style>
