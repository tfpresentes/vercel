<template>
<nav>
	<img src="../assets/logo.svg" alt="iShopee logo" name="iShopee" class="logo">
	<ul>
		<li class="ac-gn-item ac-gn-item-menu ac-gn-conheça">
				<a class="ac-gn-link ac-gn-link-mac" href="/conheça/" data-analytics-title="conheça">
					<span class="ac-gn-link-text">Conheça</span>
				</a>
			</li>
		<li class="ac-gn-item ac-gn-item-menu ac-gn-suporte">
				<a class="ac-gn-link ac-gn-link-mac" href="/suporte/" data-analytics-title="suporte">
					<span class="ac-gn-link-text">Suporte</span>
				</a>
			</li>
		<li class="ac-gn-item ac-gn-item-menu ac-gn-preços">
				<a class="ac-gn-link ac-gn-link-mac" href="/preços/" data-analytics-title="preços">
					<span class="ac-gn-link-text">Preços</span>
				</a>
			</li>
		<li class="ac-gn-item ac-gn-item-menu ac-gn-login">
				<a class="ac-gn-link ac-gn-link-mac" href="/login/" data-analytics-title="login">
					<span class="ac-gn-link-text">Login</span>
				</a>
			</li>
		<li class="ac-gn-item ac-gn-item-menu ac-gn-trial">
				<a class="ac-gn-link ac-gn-link-mac" href="/trial/" data-analytics-title="começe agora">
					<span class="ac-gn-link-text">Começe agora</span>
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
  margin: 0 20px;
}
a {
  color: #2CC694;
}

nav, ul{
  display: inline;
  align-content: center; 
}
.logo {
  display: inline;
  padding: auto;
  margin: 5%;
  height: 3em;
  /* display: inline; */
}
</style>
