<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《大蒜》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M26.9999 21C26.9999 29 30 27 30.9999 32C32.0244 37.1233 27.7379 42 22.4996 42C17.2613 42 12.9993 37.2248 12.9999 32C12.9999 27.3906 15.4998 24.5 17.9999 23C20.5 21.5 23 20 23 16" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M33 23C34 23 38.5 25 39 30C39.4523 34.5231 36.5 41.5 24 42" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/><path d="M16.001 40C8.15387 40 4.00231 35.2968 4.00098 30C4.00098 24.2947 12.001 19 14.001 18C16.001 17 17.001 15.0477 17.001 13V9C17.001 7.61973 17.6207 7 19.001 7H28.001C29.1415 7 30.001 8 30.001 9V12C30.001 14.051 31.2702 15.6727 33.0883 16.5785C33.8478 16.9576 34.6494 17.32 35.4684 17.655C38.7789 19.0093 44.001 21.1459 44.001 27C44.001 31.881 40.598 36 38.001 36" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/></svg>`
			}
		}
	}
</script>