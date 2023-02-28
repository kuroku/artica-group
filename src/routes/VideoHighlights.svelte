<script>
	import VideoCard from '$lib/components/VideoCard.svelte';
	import { Swiper, SwiperSlide } from 'swiper/svelte';
	import { Pagination, Autoplay, A11y } from 'swiper';
	import 'swiper/css';
	import 'swiper/css/pagination';
	import 'swiper/css/scrollbar';
</script>

<main>
	<h1>Videos destacados</h1>
	<p>
		Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam adipiscing elit, sed diam
	</p>
	<Swiper
		spaceBetween={50}
		slidesPerView={4}
		modules={[Autoplay, A11y]}
		pagination={{ clickable: true }}
		navigation
	>
		<SwiperSlide>
			<VideoCard />
		</SwiperSlide>
		<SwiperSlide>
			<VideoCard />
		</SwiperSlide>
		<SwiperSlide>
			<VideoCard />
		</SwiperSlide>
		<SwiperSlide>
			<VideoCard />
		</SwiperSlide>
		<SwiperSlide>
			<VideoCard />
		</SwiperSlide>
		<SwiperSlide>
			<VideoCard />
		</SwiperSlide>
	</Swiper>
</main>

<style>
	main {
		width: 100%;
		min-height: 100%;
		padding-top: 214px;
		display: grid;
		align-content: flex-start;
		overflow-x: hidden;
	}
	:global(.swiper) {
		width: 100%;
		position: relative;
		left: 89px;
		padding: 16px;
	}
	h1 {
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 130px;
		place-self: center;
	}
	p {
		max-width: 920px;
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 30px;
		line-height: 40px;
		place-self: center;
		text-align: center;
		margin-bottom: 92px;
	}
</style>
