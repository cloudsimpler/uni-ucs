<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《骑术》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M12.5804 27.5139L4 28.3194V22.6806L16.2578 17.4444V10C16.2578 10 21.9781 11.4028 22.7953 12.6111C23.6124 13.8194 22.7953 16.6389 22.7953 16.6389C26.8812 18.1157 30.7843 22.6806 30.7843 26.3056C30.7843 29.9306 29 34.5 29 34.5C27.0194 34.5 26.2898 38.7917 27.5156 40" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path d="M22 26C22 28.7614 20.2091 30 18 30C15.7909 30 14 28.7614 14 26" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/><path d="M17.3805 30C17.8186 30 18.2566 33.2 17.8186 34.8C17.3805 36.4 16.9425 37.2 13 40" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}"/><path d="M37 16C38.1046 16 39 15.1046 39 14C39 12.8954 38.1046 12 37 12C35.8954 12 35 12.8954 35 14C35 15.1046 35.8954 16 37 16Z" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-miterlimit="2"/><path d="M26.9997 30C29.4347 30.0837 33.11 28.2269 34.9997 26.9336C37.272 25.3732 35.1346 22.923 37.7243 22.3785L39.549 21C39.549 21 40.9996 23.0664 41.9996 25C42.9997 26.9336 43.5997 32.9 41.9997 36.5H33.9997L36.9997 39.5" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-miterlimit="2" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>