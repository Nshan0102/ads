<template>
    <div class="nav-container">
        <div class="nav-wrapper">
            <div class="left-side">
                <a href="#">
                    <svg width="22" height="16" viewBox="0 0 22 16" xmlns="http://www.w3.org/2000/svg">
                        <rect width="22" height="2" fill="#323232"/>
                        <rect y="7" width="16" height="2" fill="#323232"/>
                        <rect y="14" width="22" height="2" fill="#323232"/>
                    </svg>
                </a>
                <a href="#">О сервисе</a>
                <a href="#">Купить</a>
                <a href="#">Продать</a>
            </div>
            <div class="company-name">
                <a href="#">
                    <h1>Digital Threads</h1>
                </a>
            </div>
            <div class="right-side">
                <a href="#">Правила</a>
                <a href="#">
                    <img src="../assets/images/search.svg" alt="search"/>
                </a>
                <a href="#">
                    <img src="../assets/images/support.svg" alt="support"/>
                </a>
                <a href="#">
                    <img src="../assets/images/account.svg" alt="account"/>
                </a>
            </div>
        </div>
    </div>
    <div class="content">
        <div class="header">
            <div class="left-side">
                <div class="heading">
                    Привлекательные
                    аккаунты для всех
                </div>
                <div class="sub-heading">
                    Приобретите любой аккаунт по самой выгодной цене всего за 5 минут!
                </div>
                <div class="button-section">
                    <button>
                        Хочу купить
                    </button>
                </div>
            </div>
            <div class="right-side">
                <div class="heading">
                    Лучший сервис для продажи аккаунтов
                </div>
                <div class="sub-heading">
                    Если вы не знаете как и где можно продать свой аккаунт, тогда вам к нам!
                </div>
                <div class="button-section">
                    <button>
                        Хочу продать
                    </button>
                </div>
            </div>
        </div>
    </div>
    <div class="service">
        <div class="service-wrapper">
            <div class="left-side">
                <img src="../assets/images/service.png" alt="">
            </div>
            <div class="right-side">
                <div class="description">
                    DigitalThreads - сервис
                    облегчающий процесс поиска,
                    покупки и продажи аккаунтов
                    по всему миру!
                </div>
                <div class="know-more-wrapper">
                    <a class="know-more" href="#">
                        Узнать больше
                        <svg width="16" height="10" viewBox="0 0 16 10" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M0 5H15M15 5L11 1M15 5L11 9" stroke="#3878F4" stroke-width="1.5" stroke-linejoin="round"/>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'HelloWorld',
        props: {
            msg: String
        }
    }
</script>
<style scoped>

</style>
