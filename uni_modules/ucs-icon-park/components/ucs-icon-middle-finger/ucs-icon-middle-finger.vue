<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《中指》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M14.9718 26.9745C11.6511 27.5662 9.99072 29.5748 9.99072 33.0002C9.99072 38.1383 15.1438 44.0002 19.7905 44.0002C24.4372 44.0002 27.1321 44.0002 31.6802 44.0002C36.2283 44.0002 38.9907 40.1496 38.9907 37.0603C38.9907 32.7099 38.9907 28.3596 38.9907 24.0093C38.9907 22.3524 37.6476 21.0093 35.9907 21.0093H35.9816C34.3298 21.0093 32.9907 22.3484 32.9907 24.0002" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/><path d="M14.9717 30.0401V21.013C14.9717 19.3546 16.3161 18.0103 17.9744 18.0103C17.9755 18.0103 17.9765 18.0103 17.9775 18.0103C19.6381 18.012 20.9834 19.3586 20.9834 21.0192V25.0229" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/><path d="M20.9834 24.0083V7.01549C20.9834 5.35008 22.3335 4 23.9989 4C25.6643 4 27.0144 5.35008 27.0144 7.01549V24.0083" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M26.9907 23.7158V21.0034C26.9907 19.3466 28.3339 18.0034 29.9907 18.0034C31.6476 18.0034 32.9907 19.3466 32.9907 21.0034V24.0034" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>