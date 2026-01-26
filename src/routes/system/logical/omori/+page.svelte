<script>
	import Content from "$lib/components/Content.svelte";
	import Spoiler from "$lib/components/Spoiler.svelte";

</script>
<!-- no touchie this file!! -->

<svelte:head>
    <meta name="robots" content="noindex">
    <title>hii</title>
</svelte:head>

<Content title="hi chat">
    <p>we made this little website in a span of a week. we did this because</p>
    <ul class="ml-8 list-disc">
        <li><p>we wanted to improve the website</p></li>
        <li><p>work immersion</p></li>
        <li><p>and to show off my programming skills hehe (work immersion should be aligned with my course)</p></li>
    </ul>
    
    <br>
    <p>
        making this website was fun, it feels like i'm contributing to something and leaving a legacy.
        with the help of Marga (what i call her the lead developer of this project), we've successfully done it!

    </p>

    <br>

    <main class="flex flex-col gap-2">
        <details>
            <summary>why Svelte?</summary>
            <p>
                i think it's a nice framework.
                i'm learning this and i'm starting to get the hang of it.
                i know React and i've tried it (i've tried making a Next.js website),
                but i guess Svelte is okay enough for this usecase!
            </p>
            <p>they say it's a pretty fast framework and it's a compiler</p>
            <p>it doesn't require that much server-sided interaction, does it?</p>
        </details>
        <details>
            <summary>actually yeah, why is this just a static site?</summary>
            <p>
                the school doesn't have a server for hosting this type of stuff.
                i don't want to operate a server either.
                so we're locked to one option: static site generation.
            </p>
        </details>
        <details>
            <summary>who mainly built this microsite?</summary>
            <p>Marga remade the main Google Sites...</p>
            <p>me built this microsite in Svelte hosted on GitHub (which is this)...</p>
        </details>
        <details>
            <summary>can I REALLY contribute? (create pull requests)</summary>
            <p>You can, although there are untold guidelines <em>that should've been mentioned in the handbook</em>:</p>
            <ol class="ml-8 list-disc">
                <li><p>Write clean code, one that should be simple to understand.</p></li>
                <li><p>Solve a problem with the change aiming to solve that problem. (preferably the one that ALREADY exists, don't create your own problems!)</p></li>
                <li><p>Respect and follow school guidelines. Reminder: this website is for a SCHOOL!</p></li>
                <li><Spoiler><p class="text-red-800 font-serif"><strong>Look behind you at all times. At exactly 1 AM, an unknown entity appears (possibly a skinwalker) emits a quiet screeching sound and is constantly trying to catch you. I've experienced this before, if you hear any noises, ALL YOU NEED TO DO IS STOP. Wait 10 minutes and it stops.</strong></p></Spoiler></li>
                <li><p><strong>It is up to the website maintainers if they want to accept your changes.</strong></p></li>
            </ol>
        </details>
        <details>
        <summary>67</summary> 
        <p>67 type shi</p>
        </details>
        <details>
        <summary>omori</summary> 
        <p>OMORI!!</p>
        <p>SUNNY!!</p>
        <p>MARI!!</p>
        <p>AUBREY!!</p>
        <p>KEL!!</p>
        <p>HERO!!</p>
        <p>BASIL!!</p>
        </details>
        <details>
            <summary>you have a website on your own?</summary>
            <a href="https://brickwall2900.github.io" target="_blank">yes</a>
            <!-- shameless self promotion ;-; -->
        </details>
    </main>

    <br>

    <p>i wish this website well! i hope our legacy here in RMCHS gets treated well!</p>
    
    <br>

    <p>- brickwall2900</p>
    <p>Written on <time datetime="2026-01-23T12:00">January 23, 2026</time>, modified on <time datetime="2026-01-27T01:00">January 27, 2026</time></p>
</Content>