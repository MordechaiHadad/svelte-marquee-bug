<script>
    import { Marquee } from "@selemondev/svelte-marquee";
    import "@selemondev/svelte-marquee/dist/style.css";
</script>

<div class="flex w-full flex-col md:flex-row justify-center">
    <div class="flex w-full max-w-5xl">
        <Marquee direction="left" fade={true}>
            <div>Content 1</div>
            <div>Content 2</div>
            <div>Content 3</div>
        </Marquee>
    </div>
	<div class="flex flex-col md:flex-row">
		<p>hello there</p>
		<p>hello there</p>
		<p>hello there</p>
		<p>hello there</p>
		<p>hello there</p>
	</div>
</div>
