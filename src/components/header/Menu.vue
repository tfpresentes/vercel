<template>
    <nav>
        <li class="conheça">
            <a class="link-conheça" href="https://tferp.com.br/descr/erp/" data-analytics-title="conheça">
                Conheça
            </a>
        </li>
        <li class="suporte">
            <a class="link-suporte" href="https://tferp.com.br/help/" data-analytics-title="suporte">
                Suporte
            </a>
        </li>
        <li class="preços">
            <a class="link-preços" href="https://tferp.com.br/price" data-analytics-title="preços">
                Preços
            </a>
        </li>
        <li class="login">
            <a class="link-login" href="https://tferp.com.br/" data-analytics-title="login">
                Login
            </a>
        </li>
    </nav>
</template>
<style>
nav{
    display: flex;
    width: fit-content;
    list-style: none;
    flex-direction: row;
    -webkit-box-align: center;
    align-items: center;
    margin-left: 2em;
}
li {
	height: 100%;
    margin-right: 24px;
    display: flex;
    -webkit-box-align: center;
    align-items: center;
    text-align: -webkit-match-parent;
}
a {
    text-decoration: none;
    color: #511984;
}
</style>