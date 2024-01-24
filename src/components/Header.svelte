<script>
    import { base } from '$app/paths';
    export let y;

    let tabs = [
        {name: 'About', link: '#about'},
        {name: 'Pricing', link: '#pricing'},
    ];
    let linktabs = [
        {name: 'Contact', link: 'contact'}
    ]
</script>

<header class={'sticky z-[10] top-0 duration-200 px-6 flex items-center justify-between border border-solid'
+ (y > 0 ? 'py-4 bg-slate-950 border-violet-950' : 'py-6 bg-transparent border-transparent')}
>
    <h1 class="font large">
        <a href="{base}/" class='text-black duration-299 hover:text-violet-400'>
            <img src="WFLogo.jpg" class="object-cover z-[2] max-w-[5vw] max-h-[5vh]">
            <!--<b class='font-bold poppins'>WFRecordings</b>-->
        </a>
    </h1>
    <div data-sveltekit-preload-data="false" class="sm:flex items-center gap-4 hidden">
        {#each tabs as tab, index}
            <a href="{base}/{tab.link}" class="duration-299 hover:text-violet-400">
                <p>{tab.name}</p>
            </a>
        {/each}
    </div>
    <div class="flex items-center justify-between">
        {#each linktabs as tab, index}
        <div class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full bg-white
        text-slate-950">
        <a href="{base}/{tab.link}">
            <div class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20
            group-hover:translate -x-full z-0 duration-200">

            </div>
            <h4 class="relative z-9">{tab.name + (tab.name === 'Contact' ? '\u2911' : '' )}</h4>
        </a>
        </div>
        {/each}
    </div>
</header>