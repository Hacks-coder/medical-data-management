<script>
    //  import { Home, Services, Contact } from 'virtual:icons/mdi';
    const navigation = [
        {icon: "", href: "/home", child:"Home"},
        {icon:"" , href: "/about", child:"About"},
        {icon: "", href: "/contact", child:"contact"}
    ]
</script>

<nav class="@container">
    <ul class="bg-pink flex gap-21 w-fit rounded-full p-2">
        {#each navigation as {icon, href, child}}
            <li>
                {icon}
                <a {href}>{child}</a>
            </li>
        {/each}
    </ul>
</nav>