<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《差劲》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M35.9115 6.45609L41.2811 25.4561C41.6418 26.7325 40.6828 28 39.3564 28H27.8747C27.1714 28 26.651 28.6542 26.8091 29.3395L27.3086 31.5039C27.7668 33.4893 27.9139 35.5337 27.7446 37.5642L27.6527 38.6673C27.5541 39.8507 27.0393 40.9607 26.1996 41.8004C25.4315 42.5685 24.3898 43 23.3035 43H23.0644C22.4074 43 21.8021 42.6438 21.4831 42.0696L18.825 37.2851C17.6329 35.1392 15.8559 33.376 13.7009 32.2005L7.0423 28.5685C6.39977 28.2181 6 27.5446 6 26.8127V7C6 5.89543 6.89543 5 8 5H33.9869C34.882 5 35.6681 5.59473 35.9115 6.45609Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>