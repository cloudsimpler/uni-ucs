<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《四》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M25.7446 44H24.8495C19.6392 44 14.7797 41.3742 11.9243 37.016L9.72884 33.6651C8.17072 31.2869 8.63077 28.1201 10.8012 26.2836L13.0887 24.3481C13.3496 24.1273 13.5 23.8029 13.5 23.4611V7.25C13.5 5.45507 14.9551 4 16.75 4C18.5449 4 20 5.45508 20 7.25V6.25C20 4.45507 21.4551 3 23.25 3C25.0449 3 26.5 4.45508 26.5 6.25V7.25C26.5 5.45507 27.9551 4 29.75 4C31.5449 4 33 5.45508 33 7.25V11.25C33 9.45507 34.4551 8 36.25 8C38.0449 8 39.5 9.45507 39.5 11.25V30.3077C39.5 33.0387 38.6618 35.7251 37.1196 37.979C34.5557 41.7263 30.2851 44 25.7446 44Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>