<script>
	export let phone;
	export let name;
</script>

<p>
	<a class="text-lg" href="sms:{phone}">
		<span class="font-bold">{name}: </span><span class="hover:underline">{phone}</span>
	</a>
</p>
