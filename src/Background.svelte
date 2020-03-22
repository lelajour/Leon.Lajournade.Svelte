<script>
	import Pdp from "./pdp.svelte";
</script>

<div id="particles-js">
	<Pdp/>
	<script type="text/javascript" src="/particles.js/particles.js"></script>
	<script type="text/javascript" src="/particles.js/demo/js/app.js"></script>
</div>

<style>
#particles-js{
	clear: both;
	display: inline-block;
	width: 100%;
	height: 200%;
	background-color: #252525;
	background-image: url('');
	background-size: cover;
	position: absolute;
	background-position: 50% 50%;
	background-repeat: repeat;
}
</style>
