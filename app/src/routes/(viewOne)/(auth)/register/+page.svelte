<script>
	import Fill from "../../../../components/viewOne/Buttons/Fill.svelte";


	import Gradient from "../../../../components/viewOne/Buttons/Gradient.svelte";
	import Auth from "../../../../components/viewOne/otherAuth/Auth.svelte";
	import Small from "../../../../components/viewOne/Texts/Small.svelte";
	import Title from "../../../../components/viewOne/Texts/Title.svelte";

</script>

<div class="w-80 md:w-90">
    <Title text = "Registration System" />
    <Small text = "Fill in all the fields below. The full authentication process will continue when you have been given full access to our control center" /> 
</div>
<form action="" class="flex flex-col gap-5 mt-20">
    <div class="flex flex-col gap-2">
        <label for="" class="font-krona text-md">Hospital Email</label>
        <input type="text" placeholder="Email" class="w-80 h-10 bg-lightPink focus:outline-pink">
    </div>
    <div class="flex flex-col gap-2">
        <label for="" class="font-krona text-md">Password</label>
        <input type="text" placeholder="Email" class="w-80 h-10 bg-lightPink focus:outline-pink">
    </div>
    <div class="flex justify-between text-blue">
        <div class="flex gap-2"><input type="checkbox"><Small text = "Remember Me?" /></div>
        <Small text = "forgot password?" />
    </div>
    <Fill text="Register" />

    <div>
        <Auth />
    </div>
    <div class="flex justify-between">
        <Small text = "I already have an account." /> <a href="/" class="text-blue text-sm font-main" >Sign-in</a>
    </div>
</form>