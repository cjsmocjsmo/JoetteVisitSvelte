<script>
	import { page } from '$app/stores';
	// import logo from './svelte-logo.svg';
</script>

<header>
	<div class="corner">
		<!-- <a href="https://kit.svelte.dev">
			<img src={logo} alt="SvelteKit" />
		</a> -->
	</div>

	<nav>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L1,2 C1.5,3 1.5,3 2,3 L2,0 Z" />
		</svg>
		<ul>
			<li class:active={$page.path === '/'}><a sveltekit:prefetch href="/">Home</a></li>
			<li class:active={$page.path === '/about'}><a sveltekit:prefetch href="/about">About</a></li>
			<!-- <li class:active={$page.path === '/img1zoom'}><a sveltekit:prefetch href="/img1zoom"></a></li> -->
			<li class:active={$page.path === '/img1zoom'}></li>
			<li class:active={$page.path === '/img2zoom'}></li>
			<li class:active={$page.path === '/img3zoom'}></li>
			<li class:active={$page.path === '/img4zoom'}></li>
			<li class:active={$page.path === '/img5zoom'}></li>
			<li class:active={$page.path === '/img6zoom'}></li>
			<li class:active={$page.path === '/img7zoom'}></li>
			<li class:active={$page.path === '/img8zoom'}></li>
			<li class:active={$page.path === '/img9zoom'}></li>
			<li class:active={$page.path === '/img10zoom'}></li>
			<li class:active={$page.path === '/img11zoom'}></li>
			<li class:active={$page.path === '/img12zoom'}></li>
			<li class:active={$page.path === '/img13zoom'}></li>
			<li class:active={$page.path === '/img14zoom'}></li>
			<li class:active={$page.path === '/img15zoom'}></li>
			<li class:active={$page.path === '/img16zoom'}></li>
			<li class:active={$page.path === '/img17zoom'}></li>
			<li class:active={$page.path === '/img18zoom'}></li>
			<li class:active={$page.path === '/img19zoom'}></li>
			<li class:active={$page.path === '/img20zoom'}></li>
			<li class:active={$page.path === '/img21zoom'}></li>
			<li class:active={$page.path === '/img22zoom'}></li>
			<li class:active={$page.path === '/img23zoom'}></li>
			<li class:active={$page.path === '/img24zoom'}></li>
			
		</ul>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L0,3 C0.5,3 0.5,3 1,2 L2,0 Z" />
		</svg>
	</nav>

	<div class="corner">
		<!-- TODO put something else here? github link? -->
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	.corner {
		width: 3em;
		height: 3em;
	}

	/* .corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	.corner img {
		width: 2em;
		height: 2em;
		object-fit: contain;
	} */

	nav {
		display: flex;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
	}

	svg {
		width: 2em;
		height: 3em;
		display: block;
	}

	path {
		fill: var(--background);
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	li.active::before {
		--size: 6px;
		content: '';
		width: 0;
		height: 0;
		position: absolute;
		top: 0;
		left: calc(50% - var(--size));
		border: var(--size) solid transparent;
		border-top: var(--size) solid var(--accent-color);
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 1em;
		color: var(--heading-color);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}

	a:hover {
		color: var(--accent-color);
	}
</style>
