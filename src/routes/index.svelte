<script context="module">

	/** @type {import('@sveltejs/kit').Load} */
	export async function load() {
		//return {
		//	status: 200
		//}
		return {
			redirect: './one',
			status: 302
		};
	}
</script>