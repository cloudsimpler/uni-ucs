<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《吹风机》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M11 12.1383C11 12.0592 11.0587 11.9924 11.1371 11.9823L32.0822 9.27971C37.3414 8.60112 42 12.6973 42 18V18C42 23.3027 37.3413 27.3989 32.0822 26.7203L11.1371 24.0177C11.0587 24.0076 11 23.9408 11 23.8617V12.1383Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}"/><path d="M11 12L4 8V28L11 24" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M38 25L31.3061 40.8981C30.5146 42.7777 28.6738 44 26.6343 44V44C23.0091 44 20.5557 40.3051 21.9625 36.9639L27 25" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}"/><circle cx="35" cy="18" r="9" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}"/></svg>`
			}
		}
	}
</script>