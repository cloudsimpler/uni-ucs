<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《骨科》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M23.0283 36L34.0026 42.9987V24C41.6769 18.7896 44.496 13.9783 42.4597 9.56594C39.4054 2.94746 34.4604 3.38382 31.0068 5.00174C28.7044 6.08035 27.0354 9.09334 25.9998 14.0407C22.9616 7.57467 18.6951 4.34165 13.2002 4.34165C4.95788 4.34165 4.29401 14.0648 5.47501 16.446C6.656 18.8273 7.77278 20.1122 13.0007 24C12.9255 35.5632 13.4061 41.7818 14.4426 42.6557C16.3435 44.1284 19.2054 41.9098 23.0283 36Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M27 25V31" stroke="${this.colors(2)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/></svg>`
			}
		}
	}
</script>