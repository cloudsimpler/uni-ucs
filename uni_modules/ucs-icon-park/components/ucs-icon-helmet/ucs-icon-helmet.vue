<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《头盔》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M42.34 32C43.41 29.55 44 26.84 44 24C44 12.95 35.05 4 24 4C12.95 4 4 12.95 4 24H24L24.01 32C24.01 35.87 27.14 39 31.01 39C34.88 39 38.01 35.87 38.01 32H42.34Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-miterlimit="2" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M31 34C32.1 34 33 33.1 33 32C33 30.9 32.1 30 31 30C29.9 30 29 30.9 29 32C29 33.1 29.9 34 31 34Z" fill="${this.colors(0)}"/><path d="M24 32L6 36C8.23 39.17 10.45 42.37 14 44L26 37" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-miterlimit="2" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>