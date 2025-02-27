<script>
	import Fill from "../../../../components/viewOne/Buttons/Fill.svelte";
	import Auth from "../../../../components/viewOne/otherAuth/Auth.svelte";
	import Small from "../../../../components/viewOne/Texts/Small.svelte";
	import Title from "../../../../components/viewOne/Texts/Title.svelte";

</script>

<div class="w-80 md:w-90">
    <Title text = "Login System" />
    <Small text = "Fill in all the fields below. After which you can gain access to the hospital control dashbaord" /> 
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
    <Fill text="Login" />

    <div>
        <Auth />
    </div>
    <div class="flex justify-between">
        <Small text = "I don’t have an account." /> <a href="/register" class="text-blue text-sm font-main" >Sign-up</a>
    </div>
</form>