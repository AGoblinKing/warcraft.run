<script>
import "aframe";
export let name;

</script>

<style>
	h1 {
		color: purple;
	}
</style>
 <a-scene>
	<a-plane position="0 0 -4" rotation="-90 0 0" width="100" height="100" color="#7BC8A4"></a-plane>
	<a-sky color="#ECECEC"></a-sky>
</a-scene>

<div class="ui">
	<h1>Hello {name}!</h1>
</div>
