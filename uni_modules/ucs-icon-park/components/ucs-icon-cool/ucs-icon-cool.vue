<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《酷的》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M19 41C13.5 38.25 8.00129 31 5.00063 26C1.99996 21 8.3132 16.3125 12.0004 20C15.6876 23.6875 16.0004 24 16.0004 24V7.50001C16.0004 5.56701 17.5674 4 19.5004 4C21.4334 4 23.0004 5.56701 23.0004 7.50001V17C23.0004 15.067 24.5674 13.5 26.5004 13.5C28.4334 13.5 30.0004 15.067 30.0004 17V18.5C30.0004 16.567 31.5674 15 33.5004 15C35.4334 15 37.0004 16.567 37.0004 18.5V13.5C37.0004 11.567 38.5674 10 40.5004 10C42.4334 10 44.0004 11.567 44.0004 13.5V30.115C44.0004 32.0123 43.5785 33.9039 42.4268 35.4116C41.1327 37.1056 39.0179 39.3539 36 41C30.4999 44 24.5 43.75 19 41Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>