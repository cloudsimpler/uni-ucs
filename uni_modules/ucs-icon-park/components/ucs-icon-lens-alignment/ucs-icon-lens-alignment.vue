<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《镜头对准》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M14 10C14 12.2091 12.2091 14 10 14C7.79086 14 6 12.2091 6 10C6 7.79086 7.79086 6 10 6C12.2091 6 14 7.79086 14 10Z" fill="${this.colors(1)}"/><path d="M14 10C14 12.2091 12.2091 14 10 14M14 10C14 7.79086 12.2091 6 10 6C7.79086 6 6 7.79086 6 10C6 12.2091 7.79086 14 10 14M14 10H20M10 14V20" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M14 38C14 35.7909 12.2091 34 10 34C7.79086 34 6 35.7909 6 38C6 40.2091 7.79086 42 10 42C12.2091 42 14 40.2091 14 38Z" fill="${this.colors(1)}"/><path d="M14 38C14 35.7909 12.2091 34 10 34M14 38C14 40.2091 12.2091 42 10 42C7.79086 42 6 40.2091 6 38C6 35.7909 7.79086 34 10 34M14 38H20M10 34V28" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M34 38C34 35.7909 35.7909 34 38 34C40.2091 34 42 35.7909 42 38C42 40.2091 40.2091 42 38 42C35.7909 42 34 40.2091 34 38Z" fill="${this.colors(1)}"/><path d="M34 38C34 35.7909 35.7909 34 38 34M34 38C34 40.2091 35.7909 42 38 42C40.2091 42 42 40.2091 42 38C42 35.7909 40.2091 34 38 34M34 38H28M38 34V28" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M34 10C34 12.2091 35.7909 14 38 14C40.2091 14 42 12.2091 42 10C42 7.79086 40.2091 6 38 6C35.7909 6 34 7.79086 34 10Z" fill="${this.colors(1)}"/><path d="M34 10C34 12.2091 35.7909 14 38 14M34 10C34 7.79086 35.7909 6 38 6C40.2091 6 42 7.79086 42 10C42 12.2091 40.2091 14 38 14M34 10H28M38 14V20" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M17 24H31" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M24 31V17" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>