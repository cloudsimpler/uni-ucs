<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《进度5》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><circle cx="24" cy="24" r="20" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M24 4C27.2624 4 30.4754 4.79809 33.3586 6.32469C36.2418 7.85128 38.7078 10.06 40.5416 12.7583C42.3754 15.4566 43.5212 18.5626 43.8792 21.8053C44.2372 25.0481 43.7965 28.3291 42.5955 31.3625C41.3945 34.3958 39.4697 37.0893 36.989 39.2081C34.5082 41.3269 31.5467 42.8067 28.3629 43.5183C25.179 44.23 21.8694 44.152 18.7225 43.2911C15.5757 42.4303 12.6873 40.8127 10.3091 38.5794L24 24V4Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>