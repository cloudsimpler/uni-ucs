<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《化妆刷》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M14.9897 22.6108L24.8892 32.5103" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M14.9897 22.6108L6.50447 31.0961C3.7708 33.8298 3.7708 38.2619 6.50447 40.9956V40.9956C9.23814 43.7293 13.6703 43.7293 16.404 40.9956L24.8892 32.5103" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M14.9897 32.5103L10.7471 36.7529" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M24.8892 32.5102L39.7966 26.0778C42.4838 24.9183 43.605 21.6988 41.8821 19.3331C37.7183 13.6159 32.1049 8.60333 27.9636 5.53585C25.6741 3.83998 22.6337 4.8951 21.5049 7.51115L14.9897 22.6107L24.8892 32.5102Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>