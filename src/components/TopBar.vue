<template>
<nav>
	<img src="../assets/logo.svg" alt="iShopee logo" name="iShopee" class="logo">
	<ul>
		<li class="conheça">
				<a class="link-conheça" href="/conheça/" data-analytics-title="conheça">
					<span class="link-text">Conheça</span>
				</a>
			</li>
		<li class="suporte">
				<a class="link-suporte" href="/suporte/" data-analytics-title="suporte">
					<span class="link-text">Suporte</span>
				</a>
			</li>
		<li class="preços">
				<a class="link-preços" href="/preços/" data-analytics-title="preços">
					<span class="link-text">Preços</span>
				</a>
			</li>
		<li class="login">
				<a class="link-login" href="/login/" data-analytics-title="login">
					<span class="link-text">Login</span>
				</a>
			</li>
		<li class="trial">
				<a class="link-trial" href="/trial/" data-analytics-title="começe agora">
					<span class="link-text">Começe agora</span>
				</a>
			</li>
	</ul>
</nav>
</template>

<script>
export default {
  name: 'IShopee',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  font-family: NeueMontreal,Arial,sans-serif;
}
.link-trial {
	font-variant: small-caps;
	font-weight: bold;
}

nav, ul{
  display: inline;
  align-content: center; 
}
.logo {
  display: inline;
  padding: auto;
  margin: 5%;
  height: 4em;
  /* display: inline; */
}
</style>
