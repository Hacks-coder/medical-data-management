<script lang="ts">
	let { children } = $props();
	const authBG = "/auth/register.png"
</script>


<div class="@container">
	<div class="bg-white grid gap-5 @3xl:grid-cols-2">
		<div  class="flex flex-col justify-center items-center w-full @3xl:h-screen @3xl:bg-pink" >
			<img src={authBG} alt="" class="size-50 @3xl:size-100">
		</div>
		<div class="w-full flex flex-col justify-center items-center">
			{@render children()}
		</div>
	</div>
</div>
