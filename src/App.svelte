<script lang="ts">
	import {data/*<< Cannot resolve symbol 'data' */} from './comp/data';
	//import {data} from './comp/data.ts';  /* << adding .ts solves issue*/
	import Data from './comp/Data.svelte';

	console.log(data.a)

</script>
<Data></Data>
