<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《转机》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M37 28.3923V35.4066C37 39.048 34.0885 42 30.497 42C26.9054 42 23.9939 39.048 23.9939 35.4066L24.0061 13.1429C24.0061 9.19797 21.0946 6 17.503 6C13.9115 6 11 9.19797 11 13.1429V28.3923" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M43 31L37 25L31 31" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M43 10.7273C43 15.1818 37 19 37 19C37 19 31 15.1818 31 10.7273C31 9.20831 31.6321 7.75155 32.7574 6.67748C33.8826 5.60341 35.4087 5 37 5C38.5913 5 40.1174 5.60341 41.2426 6.67748C42.3679 7.75155 43 9.20831 43 10.7273Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M17 34.7273C17 39.1818 11 43 11 43C11 43 5 39.1818 5 34.7273C5 33.2083 5.63214 31.7516 6.75736 30.6775C7.88258 29.6034 9.4087 29 11 29C12.5913 29 14.1174 29.6034 15.2426 30.6775C16.3679 31.7516 17 33.2083 17 34.7273Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><circle cx="37" cy="11" r="2" fill="${this.colors(2)}"/><circle cx="11" cy="35" r="2" fill="${this.colors(2)}"/></svg>`
			}
		}
	}
</script>