<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《电话2》图标
	 * @tutorial https://ucs.cloudsimpler.com/library/ucs-iconPark
	 * @property {Number} size 图标大小
	 * @property {Number} strokeWidth 线段粗细
	 * @property {String} theme 图标大小
	 * @property {Array} fill 图标颜色，["外部描边颜色","外部填充颜色","内部描边颜色","内部填充颜色"]
	 * @property {String} strokeLinecap 图标大小
	 * @property {String} strokeLinejoin 图标大小
	 */
	export default {
		mixins: [iconMixin],
		computed: {
			iconSvg(): string {
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M39 6H9C7.34315 6 6 7.34315 6 9V39C6 40.6569 7.34315 42 9 42H39C40.6569 42 42 40.6569 42 39V9C42 7.34315 40.6569 6 39 6Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}"/><path d="M19.4401 14C19.8845 14 20.2939 14.241 20.5096 14.6295L22.006 17.3249C22.2019 17.6778 22.2111 18.1047 22.0305 18.4658L21 21C21 21 21.2517 23.2517 23 25C24.7484 26.7483 27 27 27 27L29.5266 25.9625C29.8879 25.7818 30.315 25.7911 30.6681 25.9874L33.3711 27.4902C33.7593 27.7061 34 28.1153 34 28.5594V31.6625C34 33.2428 32.5321 34.3842 31.0348 33.8789C27.9595 32.8413 23.1858 30.8656 20.1601 27.8398C17.1345 24.8142 15.1587 20.0405 14.121 16.9652C13.6158 15.4679 14.7572 14 16.3375 14H19.4401Z" fill="${this.colors(3)}" stroke="${this.colors(2)}" stroke-width="${this.strokeWidth}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>