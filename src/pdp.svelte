<script>

	import Image from "svelte-image";

</script>

<div class="pdpcontainer">
	<div class="pdp">
		<Image src="img/lelajour.jpg"/>
	</div>
</div>

<style>

div.pdpcontainer{
	border-radius: 60%;
	background: yellow;
	width: 20%;
	position: absolute;
	left: 50%;
	top: 15%;
	transform: translateX(-50%);
}

div.pdp{
	position:sticky;
	background: red;
	margin: 20%;
	border: 3px solid #73AD21;
}

</style>
