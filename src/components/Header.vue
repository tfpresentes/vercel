<template>
<div>
	<nav>
	<img src="../assets/logo.svg" alt="iShopee logo" name="iShopee" class="logo">
	<ul>
		<li class="conheça">
				<a class="link-conheça" href="https://tferp.com.br/descr/erp/" data-analytics-title="conheça">
					<span class="link-text">Conheça</span>
				</a>
			</li>
		<li class="suporte">
				<a class="link-suporte" href="https://tferp.com.br/help/" data-analytics-title="suporte">
					<span class="link-text">Suporte</span>
				</a>
			</li>
		<li class="preços">
				<a class="link-preços" href="https://tferp.com.br/price" data-analytics-title="preços">
					<span class="link-text">Preços</span>
				</a>
			</li>
		<li class="login">
				<a class="link-login" href="https://tferp.com.br/" data-analytics-title="login">
					<span class="link-text">Login</span>
				</a>
			</li>
		<li class="trial">
			<button class="trial">
				<a class="link-trial" href="/trial/" data-analytics-title="começe agora">
					<span class="link-text">Começe agora</span>
				</a>
			</button>
			</li>
	</ul>
	</nav>
</div>

</template>

<script>
export default {
  name: 'IShopee',
  props: {
    msg: String
  }
}
</script>

<style scoped>
div {
	  background-image: linear-gradient(135deg,#eb4c00,#f2a900);
}
nav{
  display: inline-block;
  align-content: center; 
  flex-wrap: nowrap;
}
.logo {
  margin: 5%;
  height: 4em;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 40px;
}
a {
  color: #fff;
  text-decoration: none;
  font-size: 2em;
}
button.trial {
	background-color: azure;
	/* padding: 20%; */
	border-radius: 30%;
	border-width: 0;
	
}
.link-trial {
	font-variant: small-caps;
	font-weight: bold;
	color: #EF8100;
}
</style>
