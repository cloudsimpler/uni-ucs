<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《向右指》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M10.0264 40.9736L10.0264 18.9736H4.02637L4.02637 40.9736H10.0264Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linejoin="${this.strokeLinejoin}"/><path fill-rule="evenodd" clip-rule="evenodd" d="M10.0264 18.9738C17.1493 12.4548 21.2772 8.71418 22.4102 7.75192C24.1096 6.30854 26.0304 6.91463 26.0304 10.5268C26.0304 14.139 20.7449 16.2222 20.7449 18.9738C20.7415 18.9902 27.5007 18.9913 41.0223 18.9771C42.6797 18.9753 44.0246 20.3174 44.0264 21.9748L44.0264 21.9779C44.0264 23.6371 42.6814 24.9821 41.0222 24.9821H33.0128C31.8039 32.9549 31.137 37.2894 31.012 37.9858C30.8244 39.0303 29.8274 40.9738 26.9583 40.9738C25.0456 40.9738 20.0683 40.9738 10.0264 40.9738V18.9738Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>