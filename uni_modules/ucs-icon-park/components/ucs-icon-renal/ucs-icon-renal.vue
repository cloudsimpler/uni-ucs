<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《肾》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M16.0004 43.9999C14.5383 39.6511 14.0665 35.9844 14.5849 32.9999C15.1033 30.0153 16.7154 28.0646 19.4211 27.1477C17.4078 33.2545 18.2328 37.7162 21.8962 40.5328C27.3912 44.7577 40.6336 42.8147 41.3511 28.5231C42.0686 14.2314 35.1948 3.9126 25.0302 3.9126C14.8656 3.9126 13.3462 14.9138 20.505 18.6471C14.1711 20.0276 10.1518 22.8611 8.44706 27.1477C6.74229 31.4342 6.60958 37.0516 8.04891 43.9999" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M30.5997 15C27.7023 16.7273 26.6522 18.3093 27.4494 19.746C28.2466 21.1828 30.0547 21.1828 32.8737 19.746" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M33.2467 26.2404C29.5062 25.4784 27.257 25.7543 26.4991 27.0681C25.3622 29.0389 30.3696 31.8942 32.1848 32.251" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>