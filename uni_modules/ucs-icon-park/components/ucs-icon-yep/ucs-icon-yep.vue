<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《胜利》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M32 42C27.2639 44.7064 21 44.5 16 42C11 39.5 7 34 7 29.5C7 26.8769 11.3562 24.9696 13.1956 24.2812C13.6561 24.1089 13.9462 23.641 13.8732 23.1548L11.5864 7.90928C11.2777 5.85104 12.8717 4 14.953 4C16.6877 4 18.1449 5.3043 18.3365 7.02835L20 22L20.8301 6.22926C20.9253 4.41897 22.421 3 24.2338 3C26.2502 3 27.8259 4.74108 27.6252 6.74756L26.5866 17.1341C26.7087 15.9225 27.7286 15 28.9466 15C31.1852 15 33 16.8148 33 19.0534L33 21.5C33 19.567 34.567 18 36.5 18C38.433 18 40 19.567 40 21.5V32.1489C40 32.7149 39.9472 33.2807 39.7471 33.8102C39.1514 35.387 37.2872 38.9788 32 42Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>