<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《孕妇》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M33 4V11.5186C40.3124 15.7131 43.6144 21.2939 42.9062 28.261C42.1979 35.2281 38.8959 40.4745 33 44" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M13.7722 4C11.6342 4.36936 10.0954 5.62186 9.15593 7.7575C7.74671 10.961 5 21.9637 5 23.7258C5 25.488 8.56767 30.2348 17.0518 37.4356C20.9831 40.7722 23.3065 40.602 24.5648 38.3638C25.8231 36.1256 24.1585 34.6902 22.0496 33.0368C18.1867 30.0083 13.102 25.215 13.102 23.111C13.102 21.7083 14.4186 17.4336 17.0518 10.287" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M8.20117 28.9409C8.71547 33.9209 9.64845 38.9209 11.0001 43.9409" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/><path d="M33 19.9443C34.5469 20.972 35.5469 22.3094 36 23.9564C36.4531 25.6035 36.5852 27.1055 36.3963 28.4624" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/></svg>`
			}
		}
	}
</script>