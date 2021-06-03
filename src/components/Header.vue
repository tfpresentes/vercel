<template>
<div class="root">
	<header class="root2">
		<div class="root3">
			<div class="root4">
				<Logo msg="Logo iShopee"/>
				<Menu msg="Menu"/>
				<CallToAction msg="Call to action"/>
			</div>
			
		</div>
		
	</header>
	
</div>

</template>

<script>	
import Logo from './header/Logo.vue'
import Menu from './header/Menu.vue'
import CallToAction from './header/CallToAction.vue'

export default {
  name: 'IShopee',
  components: {
    Logo,
	Menu,
	CallToAction,
	msg: String
  }
}
</script>

<style>
@media (min-width: 1152px) {
	.root3 {
		box-shadow: none;
	}
	.root4 {
		height: 56px;
		gap: 32px;
		padding-right: 48px;
		padding-left: 48px;
		z-index: auto;
	}
}
@media (min-width: 768px) {
	.root4 {
		padding-right: 18px;
		padding-left: 32px;
	}
}
* {
	font-family: "NOW-BLACK",Arial,sans-serif;
    box-sizing: border-box;
    margin: 0px;
    -webkit-font-smoothing: antialiased;
    appearance: none;
    text-size-adjust: 100%;
    border: 0px;
    font-weight: inherit;
    outline: 0px;
    padding: 0px;
    text-rendering: optimizelegibility;
}
div {
    display: block;
}
div.root {
    position: fixed;
    left: 0px;
    right: 0px;
    top: 0px;
    z-index: 9;
    will-change: transform;
}
header.root2 {
    display: flex;
    -webkit-box-align: center;
    align-items: center;
    position: relative;
    will-change: transform;
    transition: transform 0.2s ease 0s;
}
div.root3 {
    width: 100%;
    box-shadow: rgba(17, 17, 17, 0.1) 0px 1px 1px;
    position: relative;
}
div.root4 {
	background-image: linear-gradient(135deg,#eb4c00,#f2a900);
    display: grid;
    width: 100%;
    height: 64px;
    -webkit-box-align: stretch;
    align-items: stretch;
    gap: 8px;
    grid-template-columns: min-content minmax(160px, 1fr) minmax(min-content, auto);
    padding-right: 10px;
    padding-left: 24px;
    position: relative;
    z-index: 2;
}
</style>
