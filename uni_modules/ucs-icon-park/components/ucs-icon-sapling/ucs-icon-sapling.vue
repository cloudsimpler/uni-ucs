<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《树苗》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M26.9999 8.00001C22.3136 12.6863 23.0351 21.035 23.0351 21.035C23.0351 21.035 31.3136 21.6863 35.9999 17C40.6862 12.3137 40.0057 4.03509 40.0057 4.03509C40.0057 4.03509 31.6862 3.31372 26.9999 8.00001Z" fill="${this.colors(1)}"/><path d="M23.0351 21.035L30.9999 13.0702M23.0351 21.035C23.0351 21.035 22.3136 12.6863 26.9999 8.00001C31.6862 3.31372 40.0057 4.03509 40.0057 4.03509C40.0057 4.03509 40.6862 12.3137 35.9999 17C31.3136 21.6863 23.0351 21.035 23.0351 21.035Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M20.0001 21C23.8492 24.8434 22.9712 31.9711 22.9712 31.9711C22.9712 31.9711 15.8492 32.8434 12.0001 29C8.15094 25.1566 9.03226 18.0289 9.03226 18.0289C9.03226 18.0289 16.151 17.1566 20.0001 21Z" fill="${this.colors(1)}"/><path d="M22.9712 31.9711L16.0001 25M22.9712 31.9711C22.9712 31.9711 23.8492 24.8434 20.0001 21C16.151 17.1566 9.03226 18.0289 9.03226 18.0289C9.03226 18.0289 8.15094 25.1566 12.0001 29C15.8492 32.8434 22.9712 31.9711 22.9712 31.9711Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M23 4V44" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>