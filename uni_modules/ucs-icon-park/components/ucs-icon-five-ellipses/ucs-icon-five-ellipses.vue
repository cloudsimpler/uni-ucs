<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《五个椭圆》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M41 33C42.6569 33 44 29.4183 44 25C44 20.5817 42.6569 17 41 17C39.3431 17 38 20.5817 38 25C38 29.4183 39.3431 33 41 33Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M7 33C8.65685 33 10 29.4183 10 25C10 20.5817 8.65685 17 7 17C5.34315 17 4 20.5817 4 25C4 29.4183 5.34315 33 7 33Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M24 44C27.3137 44 30 35.0457 30 24C30 12.9543 27.3137 4 24 4C20.6863 4 18 12.9543 18 24C18 35.0457 20.6863 44 24 44Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M34 40C36.2091 40 38 32.8366 38 24C38 15.1634 36.2091 8 34 8C31.7909 8 30 15.1634 30 24C30 32.8366 31.7909 40 34 40Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M14 40C16.2091 40 18 32.8366 18 24C18 15.1634 16.2091 8 14 8C11.7909 8 10 15.1634 10 24C10 32.8366 11.7909 40 14 40Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>