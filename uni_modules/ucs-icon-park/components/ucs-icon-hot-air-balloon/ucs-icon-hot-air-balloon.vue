<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《热气球》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M39 18.3515C39 27.8545 31 36 24 36C17 36 9 27.8545 9 18.3515C9 10.6537 14.8929 4 24 4C33.1071 4 39 10.6537 39 18.3515Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M25 4C28.7 7.81854 32 14.1197 32 20C32 25.8067 28.62 32.192 25 36" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-miterlimit="2" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M23 4C18.6833 8.08726 16 13.7058 16 20C16 26.2153 18.7767 31.924 23 36" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-miterlimit="2" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M21.9994 16.0177C21.9994 16.0177 27.0654 17.0354 31 16.0177C34.9346 15 37.9995 13 37.9995 13" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M9.00047 20C9.00047 20 14.0004 22.5 18 23.5C21.9996 24.5 25.9996 24 25.9996 24" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M18 35L19.4 42.0952C19.4 42.0952 22.125 44 24 44C25.875 44 28.6 42.0952 28.6 42.0952L29.9941 35.0297L24 36L18 35Z" fill="${this.colors(1)}"/><path d="M30 35L29.9941 35.0297M29.9941 35.0297L28.6 42.0952C28.6 42.0952 25.875 44 24 44C22.125 44 19.4 42.0952 19.4 42.0952L18 35L24 36L29.9941 35.0297Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>