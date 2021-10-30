<script context="module">
	export const prerender = true;
	import img1thumb from '../lib/images/thumbs/20210617_144141-2thumb.jpg';
	import img2thumb from '../lib/images/thumbs/20210617_144150-2thumb.jpg';
	import img3thumb from '../lib/images/thumbs/20210617_144211-2thumb.jpg';
	import img4thumb from '../lib/images/thumbs/20210617_144219-2thumb.jpg';    
	import img5thumb from '../lib/images/thumbs/20210617_144600-2thumb.jpg';
	import img6thumb from '../lib/images/thumbs/20210617_144701-2thumb.jpg';
	import img7thumb from '../lib/images/thumbs/20210622_210740-2thumb.jpg';    
	import img8thumb from '../lib/images/thumbs/20210622_210743-2thumb.jpg';   
	import img9thumb from '../lib/images/thumbs/20210622_210815-2thumb.jpg';    
	import img10thumb from '../lib/images/thumbs/20210622_210818-2thumb.jpg';
	import img11thumb from '../lib/images/thumbs/20210622_210840-2thumb.jpg';    
	import img12thumb from '../lib/images/thumbs/20210622_210907-2thumb.jpg';
	import img13thumb from '../lib/images/thumbs/20210622_210933-2thumb.jpg';
	import img14thumb from '../lib/images/thumbs/20210623_070413-2thumb.jpg';
	import img15thumb from '../lib/images/thumbs/20210623_070454-2thumb.jpg';
	import img16thumb from '../lib/images/thumbs/20210623_070858-2thumb.jpg';
	import img17thumb from '../lib/images/thumbs/20210623_070912-2thumb.jpg';
	import img18thumb from '../lib/images/thumbs/20210801_201746-2thumb.jpg';
	import img19thumb from '../lib/images/thumbs/20210801_201757-2thumb.jpg';
	import img20thumb from '../lib/images/thumbs/20210801_201833-2thumb.jpg';
	import img21thumb from '../lib/images/thumbs/20210622_205739_HDR-2thumb.jpg';
	import img22thumb from '../lib/images/thumbs/20210622_205809_HDR-2thumb.jpg';
	import img23thumb from '../lib/images/thumbs/20210622_205928_HDR-2thumb.jpg';
	import img24thumb from '../lib/images/thumbs/20210623_070121_HDR-2thumb.jpg';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<div class="column">
	<a href="/img1zoom"><img src={img1thumb} alt="fuckit"></a>
	<a href="/img2zoom"><img src={img2thumb} alt="fuckit"></a>

	<a href="/img5zoom"><img src={img5thumb} alt="fuckit"></a>
	<a href="/img6zoom"><img src={img6thumb} alt="fuckit"></a>
	<a href="/img7zoom"><img src={img7thumb} alt="fuckit"></a>
	<a href="/img8zoom"><img src={img8thumb} alt="fuckit"></a>
	<a href="/img9zoom"><img src={img9thumb} alt="fuckit"></a>
	<a href="/img10zoom"><img src={img10thumb} alt="fuckit"></a>
	<a href="/img11zoom"><img src={img11thumb} alt="fuckit"></a>
	<a href="/img12zoom"><img src={img12thumb} alt="fuckit"></a>
	<a href="/img13zoom"><img src={img13thumb} alt="fuckit"></a>
	<a href="/img14zoom"><img src={img14thumb} alt="fuckit"></a>
	<a href="/img15zoom"><img src={img15thumb} alt="fuckit"></a>

	<a href="/img18zoom"><img src={img18thumb} alt="fuckit"></a>

	<a href="/img21zoom"><img src={img21thumb} alt="fuckit"></a>
	<a href="/img22zoom"><img src={img22thumb} alt="fuckit"></a>
	<a href="/img23zoom"><img src={img23thumb} alt="fuckit"></a>
	<a href="/img24zoom"><img src={img24thumb} alt="fuckit"></a>
	

	<!-- landscape pics -->
	<a href="/img3zoom"><img src={img3thumb} alt="fuckit"></a>
	<a href="/img4zoom"><img src={img4thumb} alt="fuckit"></a>

	<a href="/img16zoom"><img src={img16thumb} alt="fuckit"></a>
	<a href="/img17zoom"><img src={img17thumb} alt="fuckit"></a>

	<a href="/img19zoom"><img src={img19thumb} alt="fuckit"></a>
	<a href="/img20zoom"><img src={img20thumb} alt="fuckit"></a>
</div>

<style>
	.column {
		flex: 25%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
		border-radius: 15px;
	}

	

	@media screen and (max-width: 500px) {
		img {
			width: 180px;
		}
	}
	@media screen and (max-width: 400px) {
		img {
			width: 100px;
		}
	} 
</style>
