<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《马赛克》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M44 36H36V44H44V36Z" fill="${this.colors(0)}"/><path d="M28 36H20V44H28V36Z" fill="${this.colors(0)}"/><path d="M12 36H4V44H12V36Z" fill="${this.colors(0)}"/><path d="M44 20H36V28H44V20Z" fill="${this.colors(0)}"/><path d="M28 20H20V28H28V20Z" fill="${this.colors(0)}"/><path d="M12 20H4V28H12V20Z" fill="${this.colors(0)}"/><path d="M44 4H36V12H44V4Z" fill="${this.colors(0)}"/><path d="M28 4H20V12H28V4Z" fill="${this.colors(0)}"/><path d="M12 4H4V12H12V4Z" fill="${this.colors(0)}"/><path d="M20 12H12V20H20V12Z" fill="${this.colors(0)}"/><path d="M20 28H12V36H20V28Z" fill="${this.colors(0)}"/><path d="M36 12H28V20H36V12Z" fill="${this.colors(0)}"/><path d="M36 28H28V36H36V28Z" fill="${this.colors(0)}"/></svg>`
			}
		}
	}
</script>