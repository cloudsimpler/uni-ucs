<template>
	<ucs-svg :width="size" :height="size" :src="iconSvg" />
</template>
<script lang="uts">
	import iconMixin from "../../mixins/iconMixin.uts";
	/**
	 * @description 《燕窝》图标
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
				return `<?xml version="1.0" encoding="UTF-8"?><svg width="${this.size}" height="${this.size}" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M4.99902 32.3137L20.0339 5.94293C20.958 3.98114 22.6267 3.00024 25.0402 3.00024C28.6603 3.00024 31.0172 7.9865 31.0172 7.9865C31.0172 7.9865 32.3445 8.18426 34.999 8.57977C30.9888 8.64538 28.6699 9.45221 28.0424 11.0002C27.1012 13.3223 30.4983 15.7311 31.0172 19.0041C31.5361 22.2771 29.4663 27.8053 24.4882 30.5672C21.1694 32.4085 17.0262 32.8862 12.0583 32.0002L5.95844 43.0002" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linecap="${this.strokeLinecap}" stroke-linejoin="${this.strokeLinejoin}"/><path fill-rule="evenodd" clip-rule="evenodd" d="M14.9424 26.9782C17.5213 22.3287 19.2169 19.3432 20.0293 18.0218C21.2478 16.0397 26.2745 16.6373 24.4685 21.5845C23.2645 24.8827 20.0891 26.6806 14.9424 26.9782Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linejoin="${this.strokeLinejoin}"/><path fill-rule="evenodd" clip-rule="evenodd" d="M32.9678 32.9838C34.1099 30.2473 35.7775 28.589 37.9706 28.009C40.1637 27.4289 42.1638 27.782 43.971 29.0684C42.8455 31.6643 41.1772 33.3286 38.9661 34.0611C36.7549 34.7936 34.7555 34.4345 32.9678 32.9838Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linejoin="${this.strokeLinejoin}"/><path fill-rule="evenodd" clip-rule="evenodd" d="M26.9854 35.1143C27.7422 37.8361 29.7468 39.6565 32.9993 40.5753C36.2518 41.4942 38.9296 40.9692 41.0325 39.0005C38.4317 35.97 36.088 34.3065 34.0015 34.0101C31.915 33.7136 29.5763 34.0817 26.9854 35.1143Z" fill="${this.colors(1)}" stroke="${this.colors(0)}" stroke-width="${this.strokeWidth}" stroke-linejoin="${this.strokeLinejoin}"/></svg>`
			}
		}
	}
</script>