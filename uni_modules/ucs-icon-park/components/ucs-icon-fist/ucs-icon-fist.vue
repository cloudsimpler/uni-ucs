<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《拳头》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M34 41C28.1693 44.1747 21.5 43.5 18 42C14.5 40.5 6 35.5 6 27C6 22.7533 11.7711 20.6707 13.51 20.1396C13.7979 20.0517 14 19.7888 14 19.4878V12C14 10.067 15.567 8.5 17.5 8.5C19.433 8.5 21 10.067 21 12V9.49999C21 7.567 22.567 6 24.5 6C26.433 6 28 7.567 28 9.49999V12C28 10.067 29.567 8.5 31.5 8.5C33.433 8.5 35 10.067 35 12L35 16.4931C35.0037 14.5633 36.5693 13 38.5 13C40.433 13 42 14.5631 42 16.4961V30C42 34 38.13 38.7513 34 41Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>