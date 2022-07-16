<script context="module">

	/** @type {import('@sveltejs/kit').Load} */
	export async function load({stuff}) {

    console.log('stuff', stuff);

		return {
			redirect: './two/three', 
			status:302
		};
	}
</script>
