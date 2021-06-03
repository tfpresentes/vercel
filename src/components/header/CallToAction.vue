<template>
    <div class="cta">
        <div class="cta2">
            <div class="cta3">
                <a class="cta4" href="/trial/" data-analytics-title="começe agora">
                    Começe agora
                </a>
            </div>
            <!-- <button class="trial"></button> -->
        </div>
    </div>
</template>
<style>
div.cta {
	display: flex;
    -webkit-box-align: center;
    align-items: center;
    -webkit-box-pack: center;
    justify-content: center;
}
div.cta2 {
    display: flex;
    width: 100%;
    height: 100%;
}
div.cta3 {
    display: flex;
    width: 100%;
    height: 100%;
    min-width: 100px;
    -webkit-box-align: center;
    align-items: center;
    -webkit-box-pack: end;
    justify-content: flex-end;
    flex-direction: row;
}
a.cta4 {
    margin: 0px;
    color: rgb(130, 10, 209);
    font-weight: 500;
    letter-spacing: -0.03em;
    font-size: 1.125rem;
	    text-decoration: none;
    line-height: 1.35;
    display: inline-flex;
    -webkit-box-align: center;
    align-items: center;
    background-repeat: no-repeat;
    background-position: 0px 100%, 100% 100%;
    background-size: 47px 8%, 100% 8%;
    transition: background-size 0.2s ease-in-out 0s;
    background-image: linear-gradient(120deg, rgb(130, 10, 209) 0%, rgb(130, 10, 209) 100%), linear-gradient(120deg, transparent, transparent);
}
button.trial {
	background-color: azure;
	border-radius: 0%;
	border-width: 0;
	padding: 14px 28px;
}
.link-trial {
	font-variant: small-caps;
	font-weight: bold;
	color: #EF8100;
}
</style>