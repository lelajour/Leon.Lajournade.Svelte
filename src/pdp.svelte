<script>

	import Image from "svelte-image";

</script>

<div class="container">
	<div class="hex" style="color: rgba(255, 152, 0, 0.6)">
		<div class="pdp">
			<img class="resize" src="img/lelajour.jpg" alt="Me" align="center"/>
		</div>
	</div>
</div>

<style>

.hex:before {
	transition: 0.8s;
    content: " ";
    width: 0; height: 0;
    border-bottom: 60px solid rgba(255, 152, 0, 0.6);
    border-left: 104px solid transparent;
    border-right: 104px solid transparent;
    position: absolute;
    top: -60px;
}

.hex {
	border-radius: red;
	transition: 0.8s;
	top: 12%;
    margin-top: 30px;
    width: 208px;
    height: 120px;
    background-color: rgba(255, 152, 0, 0.6);
    position: relative;
	margin-left: auto;
	margin-right: auto;
}

.container{
	top: 6%;
	transition: 0.8s;
	left: 50%;
	transform: translateX(-50%);
	position: absolute;
	background: transparent;
	width: 208px;
	height: 239px;
	border: 3px solid yellow;
}

.container:hover{
	top: 0%;
	transition: 1s;
	width: 30%;
	height: 30%;
}

.container:hover > .hex{
	transition: 1s;
	transform: rotate(360deg);
	width: 327px;
	height: 327px;
}

.container:hover > .hex:before{
	transition: 1s;
	border-bottom: 60px solid rgba(255, 152, 0, 0.6);
    border-left: 163px solid transparent;
    border-right: 163px solid transparent;
    position: absolute;
    top: -60px;
}

.container:hover > .hex:after{
	transition: 1s;
	position: absolute;
	bottom: -60px;
	border-top: 60px solid rgba(255, 152, 0, 0.6);
	border-left: 163px solid transparent;
	border-right: 163px solid transparent;
}

.hex:after {
	transition: 0.8s;
    content: "";
    width: 0;
    position: absolute;
    bottom: -60px;
    border-top: 60px solid rgba(255, 152, 0, 0.6);
    border-left: 104px solid transparent;
    border-right: 104px solid transparent;
}

div.pdp{
	top: -42px;
	overflow: hidden;
	max-width: 200px;
	border-radius: 30%;
	margin-left: auto;
	margin-right: auto;
	margin: 30%;
	position: absolute;
	border: 3px solid #252525;
}

img.resize{
	display: block;
    margin-left: -25%;
    margin-right: auto;
    width: 150%;

}

</style>
