<script context="module">

	/** @type {import('@sveltejs/kit').Load} */
	export async function load() {
		return {
			redirect: './one/two',
			status: 302
		};
	}
</script>
