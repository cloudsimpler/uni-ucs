<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《爆米花》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M33.6961 40.8677L39 17H7L12.3039 40.8677C12.6376 42.3694 12.8045 43.1202 13.3529 43.5601C13.9013 44 14.6704 44 16.2087 44H29.7913C31.3296 44 32.0987 44 32.6471 43.5601C33.1955 43.1202 33.3624 42.3694 33.6961 40.8677Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M27 44L28 17" stroke="${this.colors(2)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M19 44L18 17" stroke="${this.colors(2)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M31 44H15" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M31 17H15" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M11.0004 16.9999C11.0004 16.9999 10.0004 13.9999 11.5004 12.4999C13.0004 10.9999 16.0004 11.4999 16.0004 11.4999C16.0004 11.4999 16.0004 8.4999 18.0004 7.4999C20.0004 6.4999 23.0004 7.99988 23.0004 7.99988C23.0004 7.99988 25.0004 4.64271 28.0004 5.49992C31.0004 6.35713 31.0004 9.99994 31.0004 9.99994C31.0004 9.99994 33.5004 9.99998 35.0004 11.9999C36.5004 13.9999 35.0004 16.9999 35.0004 16.9999" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>